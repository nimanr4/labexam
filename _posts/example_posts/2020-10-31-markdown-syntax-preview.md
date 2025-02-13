---
layout: post
title: "بدترین خاطره"

---

## نوضیح:بدترین حاطره ام ازمون میانترم ریاضی بود که من انرا فراموش کرده بودم اما خوشبختانه به ان رسیدم و امتحان دادم


## Basic Markdown Formatting

### Headings

    # This is an <h1> tag
    ## This is an <h2> tag
    ### This is an <h3> tag
    #### This is an <h4> tag
    ##### This is an <h5> tag
    ###### This is an <h6> tag

### Emphasis

    *This text will be italic*
    _This will also be italic_

    **This text will be bold**
    __This will also be bold__

    _You **can** combine them_

Result:

_This text will be italic_

_This will also be italic_

**This text will be bold**

**This will also be bold**

_You **can** combine them_

### Lists

**Inordered:**

    * Milk
    * Bread
        * Wholegrain
    * Butter

Result:

- Milk
- Bread
  - Wholegrain
- Butter

**Ordered:**

    1. Tidy the kitchen
    2. Prepare ingredients
    3. Cook delicious things

Result:

1. Tidy the kitchen
2. Prepare ingredients
3. Cook delicious things

### Images

    ![Alt Text](url)

Result:

![m'lady](http://i.imgur.com/v8IVDka.jpg)

### Links

    [link](http://example.com)

Result:

[link](http://example.com)

### Blockquotes

    As Kanye West said:

    > We're living the future so
    > the present is our past.

Result:

As Kanye West said:

> We're living the future so
> the present is our past.

### Horizontal Rules

    ---

Result:

---

### Code Snippets

    Indenting by 4 spaces will turn an entire paragraph into a code-block.

Result:

    .my-link {
        text-decoration: underline;
    }

### Reference Lists & Titles

    **The quick brown [fox][1], jumped over the lazy [dog][2].**

    [1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
    [2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

Result:

**The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

### Escaping

    \*literally\*

Result:

\*literally\*

### Embedding HTML

    <button class="button-save large">Big Fat Button</button>

Result:

<button class="button-save large">Big Fat Button</button>

## Advanced Markdown

Note: Some syntax which is not standard to native Markdown. They're extensions of the language.

### Strike-throughs

    ~~deleted words~~

Result:

~~deleted words~~

### Automatic Links

    https://ghost.org

Result:

https://ghost.org

### Markdown Footnotes

Work in [Ghost](https://ghost.org/):

    The quick brown fox[^1] jumped over the lazy dog[^2].

    [^1]: Foxes are red
    [^2]: Dogs are usually not red

Result:

The quick brown fox[^1] jumped over the lazy dog[^2].

[^1]: Foxes are red
[^2]: Dogs are usually not red

## GitHub Flavored Markdown

### Syntax Highlighting

    ```javascript
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    ```

Result:

```javascript
function fancyAlert(arg) {
  if (arg) {
    $.facebox({ div: "#foo" });
  }
}
```

### Task Lists

    - [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
    - [x] list syntax required (any unordered or ordered list supported)
    - [x] this is a complete item
    - [ ] this is an incomplete item

Result:

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Tables

You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:

```
First Header | Second Header | Third Header |
------------ | ------------- ----------------
Content from cell 1 | Content from cell 2 | Content from cell 3 |
Content in the first column | Content in the second column | Content in the third column |
Content in the forth row A | Content in the forth row B | Content in the forth row C |
```

| First Header                | Second Header                | Third Header                |
| --------------------------- | ---------------------------- | --------------------------- |
| Content from cell 1         | Content from cell 2          | Content from cell 3         |
| Content in the first column | Content in the second column | Content in the third column |
| Content in the forth row A  | Content in the forth row B   | Content in the forth row C  |

## References

- http://blog.ghost.org/markdown/
- https://guides.github.com/features/mastering-markdown/
