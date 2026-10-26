---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
在集合的指定位置插入指定幻灯片的副本。

### 返回

插入的幻灯片。



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
内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。
手动克隆母版幻灯片既不会被阻止，也不会被注册。
如果您需要对克隆过程进行更细致的控制，请使用
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** 或
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** 来克隆幻灯片，以及
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** 来克隆母版。


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
在集合的指定位置插入指定幻灯片的副本。

### 返回

插入的幻灯片。



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 新幻灯片的索引。 |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide) | 新幻灯片的版式幻灯片。 |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
在集合的指定位置插入指定源幻灯片的副本。
将自动从指定的母版中选择合适的版式（合适的版式是与源幻灯片的版式具有相同类型或名称的版式）。如果没有合适的版式，则源幻灯片的版式将被克隆（如果 allowCloneMissingLayout 为 true）或抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。

### 返回

插入的幻灯片。



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 新幻灯片的索引。 |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide) | 新幻灯片的母版幻灯片。 |
| allow_clone_missing_layout | **bool** | 如果在指定的母版中没有合适的版式，则版式将被克隆 <br/><br/>            源幻灯片（如果 allowCloneMissingLayout 为 true）或 <br/><br/>            PptxEditException 将被抛出（如果 allowCloneMissingLayout 为 false）。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果在指定的母版中没有合适的版式且 <br/>            allowCloneMissingLayout 为 false，则抛出此异常。 |



### 另请参见
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`ISlideCollection`](/slides/python-net/zh/aspose.slides/islidecollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)