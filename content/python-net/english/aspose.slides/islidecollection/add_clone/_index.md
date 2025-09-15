---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islidecollection/add_clone/
weight: 10
---


## add_clone {#islide}
Adds a copy of a specified slide to the end of the collection.

### Returns

New slide.



```python
def add_clone(self, source_slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | Slide to clone. |

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
[`ISlideCollection.add_clone`](/slides/python-net/aspose.slides/islidecollection/add_clone) or
[`ISlideCollection.add_clone`](/slides/python-net/aspose.slides/islidecollection/add_clone) for cloning slides,
[`IGlobalLayoutSlideCollection.add_clone`](/slides/python-net/aspose.slides/igloballayoutslidecollection/add_clone) or
[`IGlobalLayoutSlideCollection.add_clone`](/slides/python-net/aspose.slides/igloballayoutslidecollection/add_clone) for cloning layouts and
[`IMasterSlideCollection.add_clone`](/slides/python-net/aspose.slides/imasterslidecollection/add_clone) for cloning masters.


## add_clone {#islide-isection}
Adds a copy of a specified slide to the end of the specified section.

### Returns

New slide.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | Slide to clone. |
| section | [`ISection`](/slides/python-net/aspose.slides/isection) | Section for a new slide. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) |  |


## add_clone {#islide-ilayoutslide}
Adds a copy of a specified slide to the end of the collection.

### Returns

New slide.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | Slide to clone. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide) | Layout slide for a new slide. |


## add_clone {#islide-imasterslide-bool}
Adds a copy of a specified source slide to the end of the collection.
            Appropriate layout will be selected automatically from the specified 
            master (appropriate layout is the layout with the same Type or Name as 
            of layout of the source slide). If there is no appropriate layout then
            layout of the source slide will be cloned (if allowCloneMissingLayout 
            is true) or PptxEditException will be thrown (if allowCloneMissingLayout
            is false).

### Returns

New slide.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | Slide to clone. |
| dest_master | [`IMasterSlide`](/slides/python-net/aspose.slides/imasterslide) | Master slide for a new slide. |
| allow_clone_missing_layout | **bool** | If there is no appropriate layout in specified master then layout of the <br/><br/>            source slide will be cloned (if allowCloneMissingLayout is true) or <br/><br/>            PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | Thrown if there is no appropriate layout in specified master and <br/>            allowCloneMissingLayout is false. |



### See Also
* class [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/aspose.slides/imasterslide)
* class [`ISection`](/slides/python-net/aspose.slides/isection)
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* class [`ISlideCollection`](/slides/python-net/aspose.slides/islidecollection)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

