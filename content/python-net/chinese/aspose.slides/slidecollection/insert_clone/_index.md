---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
在集合的指定位置插入指定幻灯片的副本。

### 返回

已插入的幻灯片。



```python
def insert_clone(self, index, source_slide):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 新幻灯片的索引。 |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |

### 备注

在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。  
Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.  
Manual cloning of master slides will be neither prevented nor registered.  
如果您需要对克隆过程进行更多控制，请使用  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** or  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides and  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
在集合的指定位置插入指定幻灯片的副本。

### 返回

已插入的幻灯片。



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 新幻灯片的索引。 |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide) | 新幻灯片的布局幻灯片。 |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
在集合的指定位置插入指定源幻灯片的副本。  
将自动从指定的母版中选择合适的版式（合适的版式是与源幻灯片的版式具有相同类型或名称的版式）。如果没有合适的版式，则版式的 <br/><br/>            源幻灯片将被克隆（如果 allowCloneMissingLayout 为 true）或 <br/><br/>            PptxEditException 将被抛出（如果 allowCloneMissingLayout 为 false）。

### 返回

已插入的幻灯片。



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 新幻灯片的索引。 |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide) | 新幻灯片的母版幻灯片。 |
| allow_clone_missing_layout | **bool** | 如果在指定的母版中没有合适的版式，则版式的 <br/><br/>            源幻灯片将被克隆（如果 allowCloneMissingLayout 为 true）或 <br/><br/>            PptxEditException 将被抛出（如果 allowCloneMissingLayout 为 false）。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果在指定的母版中没有合适的版式且 <br/>            allowCloneMissingLayout 为 false，则抛出。 |

### 参见
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 类 [`SlideCollection`](/slides/python-net/zh/aspose.slides/slidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)