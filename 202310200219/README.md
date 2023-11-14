# My collection of notes from the 2023 Skilstak Beginner Boost

Headings begin with octothorpes (#). Include a blank line after the heading to separate from following paragraph.

```md
# Heading 1

Paragraph

## Heading 2

```

## Formatting

Just use stars.

* Use *one star* for italic (em).
* Use **two stars** for bold (strong).
* Use ***three stars*** for bold/italic (strong em).
* This is `monospace` stuff (pre, code).
* Use dollar signs for inline math $\sqrt{3x-1}+{1+x}^2$

* First bullet
* Second bullet

But, when I have an ordered or numbered list:

1. First
2. Second
3. Third

```go
package main

import "fmt"

func main() {
  fmt.Println("Hello world!")
}
```

What if I want *italic* or **bold** or ***bolditalic***

How about something that looks like `code`?

## Links

Here is a [link to rwx.gg](https://rwx.gg).

## Images
Images are just like links with an (!) in front of the square brackets.
![lachlan-dempsey-6VPEOdpFNAs-unsplash](https://github.com/ryankisslinger/boost-notes/assets/24976000/5f75d56f-caa1-4018-99f5-ede4895b01bb)


## Hard Breaks
Roses are red  
Violets are blue  

## Verbatim blocks
  ```
	Roses are red
	Violets are blue
  ```

## Blockquotes
Blockquotes are for quotations and only quotations.

Begin each line of the block with a greater-than sign.

Usually you will just have a single paragraph:

> This is the first part of the quote.
  >
  > This is the second part.

~~~~
> This is the first part of the quote.
  >
  > This is the second part.
~~~~

## Comments
Comments are just simple HTML comments, which were inherited from SGML, dating back decades.
```markdown
<!-- This is a comment  -->

<p>This is a markdown paragraph with <!-- another --> comment in it. </p>
```
