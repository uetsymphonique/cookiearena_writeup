After trying some seperators as `|`, `||`, `&` and `&&`, realizing that the validation has checked these situations.
So we try to using endline to separate the command injection:
![img.png](img.png)
Now trying to see the content of `/flag.txt` by using `cat`, but it's an invalid input because of whitespace.
![img_1.png](img_1.png)
So we using input redirection `<` instead of the whitespace:
![img_2.png](img_2.png)
Flag: `EHC{C0mm4nd_1nj3ct10n_16eda82e05fa1d12be27752bd7a1e8e0}` 