# Example Markdown Source

Start writing here! Replace any of this placeholder text with your opus. We've included a few examples of commonly used book elements, but you can delete them. You can add any of these elements using the buttons in the toolbar, as well.

You can use [links](https://help.github.com/articles/markdown-basics/), _italics_ and **bold**.

## Executables

In code blocks you can run python code. Usually you will start by importing libraries needed for your example.

<pre data-code-language="python"
     data-executable="true"
     data-type="programlisting">
# Import numpy.
import numpy as np
# Import mathplotlib
import matplotlib.pyplot as plt

</pre>

#### Output
You can use math-tex such as <span class="math-tex" data-type="tex">\\(8*8=64\\)</span> to illustrate your code.

Add some simple output:

<pre data-code-language="python"
     data-executable="true"
     data-type="programlisting">
print "Hello World!"
</pre>

Or a more complex graph:

<pre data-code-language="python"
     data-executable="true"
     data-type="programlisting">

plt.plot([1,19,21,8,6])
plt.ylabel('Speed')

plt.show()
</pre>
