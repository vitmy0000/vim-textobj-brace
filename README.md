# vim-textobj-brace

`vim-textobj-brace` is a quick shortcut for having to reach for the specific
text objects for `[]`, `{}`, or `()`.

The `ij` and `aj` text objects will select the innermost of either of the three
brace or bracket characters.


Requires [vim-textobj-user](https://github.com/kana/vim-textobj-user).


# Fork from [Julian/vim-textobj-brace](https://github.com/Julian/vim-textobj-brace)
Fix bug:

```
(
foo
b|ar
)
```
`|` indicates cursor position, type `dij`, results in
```
(
```
