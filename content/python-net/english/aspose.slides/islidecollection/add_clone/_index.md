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
| source_slide | ISlide | Slide to clone. |

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide. or
            Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste. for cloning slides,
            Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide. or
            Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide. for cloning layouts and
            Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide. for cloning masters.



## add_clone {#islide-isection}
Adds a copy of a specified slide to the end of the collection.

### Returns

New slide.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | ISlide | Slide to clone. |
| section | ISection |  |

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide. or
            Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste. for cloning slides,
            Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide. or
            Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide. for cloning layouts and
            Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide. for cloning masters.



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
| source_slide | ISlide | Slide to clone. |
| dest_layout | ILayoutSlide |  |

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide. or
            Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste. for cloning slides,
            Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide. or
            Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide. for cloning layouts and
            Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide. for cloning masters.



## add_clone {#islide-imasterslide-bool}
Adds a copy of a specified slide to the end of the collection.

### Returns

New slide.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | ISlide | Slide to clone. |
| dest_master | IMasterSlide |  |
| allow_clone_missing_layout | bool |  |

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide. or
            Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste. for cloning slides,
            Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide. or
            Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide. for cloning layouts and
            Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide. for cloning masters.



