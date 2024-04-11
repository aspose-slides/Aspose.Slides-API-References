---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/slidecollection/insert_clone/
weight: 30
---


## insert_clone {#int-ISlide}
Inserts a copy of a specified slide to specified position of the collection.

### Returns

Inserted slide.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of new slide. |
| source_slide | ISlide | Slide to clone. |

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide. or
            Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste. for cloning slides and
            Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide. for cloning masters.



## insert_clone {#int-ISlide-ILayoutSlide}
Inserts a copy of a specified slide to specified position of the collection.

### Returns

Inserted slide.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of new slide. |
| source_slide | ISlide | Slide to clone. |
| dest_layout | ILayoutSlide |  |

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide. or
            Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste. for cloning slides and
            Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide. for cloning masters.



## insert_clone {#int-ISlide-IMasterSlide-bool}
Inserts a copy of a specified slide to specified position of the collection.

### Returns

Inserted slide.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of new slide. |
| source_slide | ISlide | Slide to clone. |
| dest_master | IMasterSlide |  |
| allow_clone_missing_layout | bool |  |

### Remarks

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide. or
            Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste. for cloning slides and
            Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide. for cloning masters.



