
# Assignment for week 2

Use the following table to provide us with

|name | exam number|
|----|----|
|Lucas Kraimaat| 1280335|

In the following cell type in markdown the text with a link and an image that you can find [here](http://janboone.github.io/programming-for-economists/_downloads/markdown_text_programming_for_economists.html).

Note that we are interested in seeing bold text, italics and math etc. Use your browser to find the image's address.

After you type your text, press SHIFT-ENTER and check whether the text looks the same as [here](http://janboone.github.io/programming-for-economists/_downloads/markdown_text_programming_for_economists.html).

# This is a section

## This is a subsection

A bullet list looks _like this_:
* bullet 1
* bullet 2
* __bullet 3__

We can like (shouldn't it be link?) to this [wonderful page](http://janboone.github.io/programming-for-economists/index.html) 

And we can add a picture to the text as well.

![alt text](http://images2.mtv.com/uri/mgid:file:docroot:mtv.com:/crop-images/2013/11/05/the_who_umg.jpg?enlarge=false&maxdimension=1300&matte=true&matteColor=black&quality=0.85)

Let's type some maths:
\begin{equation}
sin(x)+ cos(x) = 2
\end{equation}

As a rule i really like this line.

We are done.


```python
type here the text in markdown
```

Install plotly on your computer using these [instructions to install plotly.](https://plot.ly/python/getting-started/) Note that with anaconda you can use "conda install plotly" instead of "pip install".

Now let us check whether it works, run the code in the following cell:


```python
from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot
from plotly.graph_objs import Bar, Scatter, Figure, Layout
init_notebook_mode(connected=True                  
from numpy import arange
range_x = arange(-2,2.1,0.1)
iplot([{"x": range_x, "y": [x**2 for x in range_x]}])
```


      File "<ipython-input-2-5c7a67b4b10e>", line 4
        from numpy import arange
           ^
    SyntaxError: invalid syntax
    


Do you see the graph in your notebook? If not, ask us during the tutorial!

After you have finished, we need to upload this notebook on github. Make sure that you upload the file on the github page of each group member.

Instructions on how to upload this on github can be found [on this page](http://janboone.github.io/programming-for-economists/github.html). This page has two screencasts: one shows how to drag the notebook onto your github page, the other shows how you can use the command line to upload your notebook.


Remember to update the README file in your repository to include a link to this notebook on github.


