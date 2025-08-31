---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidecollection/insert_clone/
weight: 60
---


## insert_clone {#int-asposeslidesislide}
Inserts a copy of a specified slide to specified position of the collection.

### Returns

Inserted slide.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Index of new slide. |
| source_slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | Slide to clone. |

### Examples

The following example shows how to clone at another position within Presentation.

            The following example shows how to clone at another position within Presentation.

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
[`SlideCollection.insert_clone`](/slides/python-net/aspose.slides/slidecollection/insert_clone) or
[`SlideCollection.insert_clone`](/slides/python-net/aspose.slides/slidecollection/insert_clone) for cloning slides and
[`IMasterSlideCollection.add_clone`](/slides/python-net/aspose.slides/imasterslidecollection/add_clone) for cloning masters.


## insert_clone {#int-asposeslidesislide-asposeslidesilayoutslide}
Inserts a copy of a specified slide to specified position of the collection.

### Returns

Inserted slide.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Index of new slide. |
| source_slide | [`ISlide`](/slides/python-net/aspose.slides/islide) | Slide to clone. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/aspose.slides/ilayoutslide) | Layout slide for a new slide. |


## insert_clone {#int-asposeslidesislide-asposeslidesimasterslide-bool}
Inserts a copy of a specified source slide to specified position of the collection.
            Appropriate layout will be selected automatically from the specified 
            master (appropriate layout is the layout with the same Type or Name as 
            of layout of the source slide). If there is no appropriate layout then
            layout of the source slide will be cloned (if allowCloneMissingLayout 
            is true) or PptxEditException will be thrown (if allowCloneMissingLayout
            is false).

### Returns

Inserted slide.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Index of new slide. |
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
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* class [`SlideCollection`](/slides/python-net/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

