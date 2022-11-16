# 105-Unit-3
This is a repository containing instructional materials and sample datasets for Prof. Gotzler's Fall 2022 sections of ENGL-105 at the University of North Carolina, Chapel HIll.

The repository contains 3 python notebooks: 
1. module on basic topics in coding with Python3
2. module on getting started with the Pandas package
3. module on using the Pandas package for data analyis 

These materials have been adapted from the excellent lessons created by the staff at the [Research Hub](https://github.com/UNC-Libraries-data) of UNC's Davis Library.

## Guidance on README files
When writing your own README files remember the contents of this document should contain:

- PROVENANCE (where did this data/code come frome?)
- PUPROSE (what/who is this data/code for?)
- POTENTIAL (why was this repo created, and what *might* people do with it?)

You'll also need to include any procedural information, whether functional or contextual, that users will need in order to access, open, and run your python notebooks. 

## Adding Data Visualizations
You can also add an inline image to share data visualizations. These should demonstrate something meaningful about the data, and give users a sense of the kinds of uses they might put it to.

This visualiztion shows the correlation of primary care and mental health provision by county, and was created using the "RI_Subset" data that we compiled in our Pandas tutorials.

![data-viz](/data/data-viz-demo.png)

To add an inline image, use the following Markdown: `![alt-text](image.jpg)` — the "alt-text" is what will appear if the image fails to load, and "image.jpg" should be replaced with the relative file path for your image.

So, for example, to create the inline image above I used the following: 
`![data-viz](/data/data-viz-demo.png)`
- if the image fails to load, the text 'data-viz' will appear
- the image file is located in my data folder, so it's relative file path is `/data/data-viz-demo.png`
