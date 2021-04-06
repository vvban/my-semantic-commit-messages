# My semantic commit messages

This is the semantics that I like.<br>

Format: `<type>=<scope1|scope2|...>: <subject>`<br>
  
`<scope>` is optional<br>
  
```
PF=index.js: add the super feature
^^ ^-------^ ^-------------------^
|  |         |
|  |         +-> Summary in present tense.
|  +--> Scope
+-------> Type: PF, etc.
```
### [Types](https://github.com/vvban/my-semantic-commit-messages/blob/main/commit-messages-crib.md):
<table>
    <tr>
        <th>prod changes</th>
        <th>dev changes</th>
        <th>test changes</th>
        <th>&lt; scope of the commit</th>
    </tr>
    <tr>
        <td>PF</td>
        <td>DF</td>
        <td>TF</td>
        <td><ins>f</ins>eature &lt; release of an important feature</td>
    </tr>
    <tr>
        <td>PW</td>
        <td>DW</td>
        <td>TW</td>
        <td><ins>w</ins>rite &lt; writing some code</td>
    </tr>
    <tr>
        <td>PX</td>
        <td>DX</td>
        <td>TX</td>
        <td>fi<ins>x</ins> &lt; bug fixes</td>
    </tr>
    <tr>
        <td>PD</td>
        <td>DD</td>
        <td>TD</td>
        <td><ins>d</ins>ocumentation &lt; change doc (markdown, etc), edit comments</td>
    </tr>
    <tr>
        <td>PA</td>
        <td>DA</td>
        <td>TA</td>
        <td><ins>a</ins>rchitecture &lt; create new empty files, folders</td>
    </tr>
    <tr>
        <td>PS</td>
        <td>DS</td>
        <td>TS</td>
        <td><ins>s</ins>tyle &lt; formatting, add spaces, etc</td>
    </tr>
    <tr>
        <td>PR</td>
        <td>DR</td>
        <td>TR</td>
        <td><ins>r</ins>efactor &lt; refactoring code, eg. renaming a variable</td>
    </tr>
    <tr>
        <td>PP</td>
        <td>DP</td>
        <td>TP</td>
        <td><ins>p</ins>erformance &lt; code change that improves performance</td>
    </tr>
</table>


#### References to other semantics:
- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
