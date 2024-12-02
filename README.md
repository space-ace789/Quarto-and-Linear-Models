# Quarto-and-Linear-Models-Files-
Stuff from the week 2 practical on linear models and creating reproducible research with quarto.

## Quarto Formatting/syntax not already in notes.

Six levels of heading (large to small) are possible when prefixed by 1-6 hashes (#), as
above.\
A forward-slash at the end of a line starts a new paragraph.\
Words inside a pair of tildes (~~) are formatted struck through, like this.\
Numbers inside a pair of carets (^) are formatted as superscripts, like this for cm2.\
Numbers inside a pair of tildes (~) are formatted as subscripts, like this for base10.\
Two dashes are formatted as an en-dash, like this –.\
Three dashes are formatted as an em-dash, like this —.\
Words inside a pair of asterisks are formatted in italic, like this\
Words inside a double pair of asterisks are formatted in bold, like this.\
Words inside (<ins </ins>) are underlined.\

Hyperlinks can be added in two ways. The web address can be put inside a pair of less-than
and greater-than characters (first link below). Or, the web address is put in parentheses and
the word ‘link’ inside square brackets is put in front of it (second link below). The word link
can be changed (as in the third link below where link’ has been changed to r4ds).

Equations can be set on their own when written inside a double pair of dollar signs ($).

Footnotes are put inside square brackets after a caret as shown in the example that applies
to this quote (bottom margin).

Page breaks are inserted with the word newpage preceded by a backslash - see the example
below that puts the references on a new page.

## Quarto vs R markdown

<ins> Chunk option positioning </ins>

In R markdown chunk options are separate from the chunk content, in Quarto they are on
the first lines of the chunk.
- R markdown—Options inside curly braces separated by commas.
- Quarto—Options on separate lines prefixed hash-pipe like this: #|


<ins>Chunk option syntax</ins>

R markdown uses block capitals and equals signs, Quarto uses lowercase and colons. Luckily,
R markdown syntax will usually work in Quarto documents.
- R markdown—include = FALSE
- Quarto—include: false

## New features in Quarto

Callout blocks - This new feature formats blocks of text so that they stand out.\
Diagrams - Quarto can produce flowcharts, Gantt charts and other types types of charts from plain text
syntax code - see the example on the Quarto website.
