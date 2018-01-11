My attempts to create non-ugly reusable basic plots in matplotlib's object-oriented interface

Born out of frustration with changing anything with the wonky "state machine" api, or wrappers like Seaborn.

Goal is: 

- Attractive

- Clean (minimal chart junk)

- Printable (greyscale, suitable for reproduction in, e.g., academic journals)

- Reusable (so I can just bang them out for print purposes over and over in SVG)

- Minimally functional (pass in some data and options, get a chart---no silliness with global state)

Once enough of these are created and I've settled on final attractiveness, I might turn this into a library.

Right now, the only thing that exists is basic x-y scatterplot.  I want to at least add a histogram soon.
