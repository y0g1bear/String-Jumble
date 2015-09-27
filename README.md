# String Jumble (Level II)

The purpose of this challenge is to gain proficiency with manipulating lists.

Write and submit a Python program that accepts a string from the user and 
prints it back in three different ways:

* With all letters in reverse.
* With all words in **correct** order, but letters **reversed** *within* the words.
* With words in **reverse** order, but letters within each word in the **correct** order.

Output of your program should look like this:

```
Please enter a string of text (the bigger the better): There are a few techniques or tricks that you may find handy
You entered "There are a few techniques or tricks that you may find handy". Now jumble it:
ydnah dnif yam uoy taht skcirt ro seuqinhcet wef a era erehT
handy find may you that tricks or techniques few a are There
erehT era a wef seuqinhcet ro skcirt taht uoy yam dnif ydnah
```

There are a few techniques or tricks that you may find handy when working on this 
challenge. If you see something here that sounds useful, feel free to learn more 
about it! You don't necessarily need *any* of these techniques to solve the challenge.

* `'a string has several characters'.count('a')` will return 5, which is the number of 
  times the character `'a'` appears in the string: `'a string has several characters'`.
* `zip([1,4,2],['a','z','q'])` will return an iterator for a list of tuples (another type 
  of list) like this: `[(1, 'a'), (4, 'z'), (2, 'q')]`
* If mylist is a list like `[435, 2, 45, 2]` vthen `mylist.sort()` will *change* it 
  to: `[2, 2, 45, 435]`
* If mylist is a list like `[435, 2, 45, 2]` then `mylist.append(99)` will *change* 
  it to: `[435, 2, 45, 2, 99]`
* If mylist is a list like `[435, 2, 45, 2]` then `mylist[-1]` will return `2`, the 
  last element in the list.
* You can get the length of a string, or number of elements in a list using the 
  builtin `len()` function. For example: `len([435, 2, 45, 2])` will return `4`.
* If you `import string` then use `string.ascii_lowercase` to get a string with 
  the letters a-z in it.
