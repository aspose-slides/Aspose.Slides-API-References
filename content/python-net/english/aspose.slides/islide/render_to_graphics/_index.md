---
title: render_to_graphics method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islide/render_to_graphics/
weight: 90
---


## render_to_graphics {#asposeslidesexportirenderingoptions-asposepydrawinggraphics}
Renders certain slide to a Graphics object.


```python
def render_to_graphics(self, options, graphics):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| graphics | **aspose.pydrawing.Graphics** | The object where to render to. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


## render_to_graphics {#asposeslidesexportirenderingoptions-asposepydrawinggraphics-asposepydrawingsize}
Renders certain slide to a Graphics object using specified size.


```python
def render_to_graphics(self, options, graphics, rendering_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| graphics | **aspose.pydrawing.Graphics** | The object where to render to. |
| rendering_size | **aspose.pydrawing.Size** | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


## render_to_graphics {#asposeslidesexportirenderingoptions-asposepydrawinggraphics-float-float}
Renders certain slide to a Graphics object with custom scaling.


```python
def render_to_graphics(self, options, graphics, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| graphics | **aspose.pydrawing.Graphics** | The object where to render to. |
| scale_x | **float** | The scale for rendering the slide (1.0 is 100%) in the x-axis direction. |
| scale_y | **float** | The scale for rendering the slide (1.0 is 100%) in the y-axis direction. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |



### See Also
* class [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions)
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

