# Visual editing practice: foreground and background

The idea of this exercise is to practice extracting an image from its context, so you can repurpose it in another context. To begin, expand the zipped archive (images.zip) to find a set of five images to work with.

Starting with the image of a hot-air balloon (beverly-and-pack--fly-me-to-the-moon.jpg), experiment with the following GIMP tools / approaches to select just the balloon (or just the moon, etc). Once it's selected, you can copy it and paste it into a new layer where it can be resized, repositioned, recolored, etc.

## Selecting objects
A few options to consider:
* **Scissors select** (edge detection). Using a series of single clicks, trace your way around the border between the foreground and the background. If the contrast is high enough, GIMP should automatically curve the selection lasso along the boundary line.
* **Fuzzy select** ("magic wand"). This tool detects contiguous pixels based on color similarities. You can adjust the sensitivity (ie. how similar is "similar"?) in the tool options pane. It's often particularly useful to select a relatively monochrome _background_, allowing you to then Invert Selection to extract a foreground object.
* **Additive/subtractive selection**. With all the select tools, you can hold down combinations of control, shift, and alt/command to change whether you're _replacing_ an existing selection (the default), _adding_ to it, _subtracting_ from it, or finding the _intersection_ between old and new. Try it with the **shape select** (i.e. rectangle or ellipse) and **free select** (lasso) tools – or with either AI-assisted tool above – to iteratively get closer to the selection you want.

NB: Because you can edit selection anchors until you're satisfied, you'll want to **press Enter**, double-click inside the selection, or switch to another tool **to confirm the selection.**


## Pasting objects
### A new layer in the same file
When you copy a selection and paste it, GIMP first opens a "floating layer"; you can click the green page button in the Layers pane to anchor it as a new, independent layer.


### A new layer in another file
To import an image into an existing project, use File > Open as Layers and select the source file.

You can also copy a selection onto the clipboard in one project, switch to another project, and paste into a new layer there.

<div class="alert alert-success">
Play around with the selection tools and moving objects from one background to another!
</div>


## Manipulating objects

Most GIMP transformation tools act on layers, rather than on selections. Once you have multiple layers in your project, see what happens if you try the Move tool, the Scale tool, etc...

