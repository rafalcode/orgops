# orgops

# commands
to render and org mode into a pandoc mdown
pandoc -s rus.org -o rus.text
to generate a slideshow pdf
pandoc -t beamer rus.text -o rus.pdf
(note how slides are separator by top level headings.
