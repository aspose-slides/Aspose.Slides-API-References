---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
将指定幻灯片的副本添加到集合的末尾。

### 返回

新幻灯片。



```python
def add_clone(self, source_slide):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |

### 备注

在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。  
内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。  
手动克隆母版幻灯片既不会被阻止，也不会被注册。  
如果需要对克隆过程进行更多控制，请使用  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** 或  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** 用于克隆幻灯片，  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** 或  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** 用于克隆布局，以及  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** 用于克隆母版。


## add_clone(self, source_slide, section) {#islide-isection}
将指定幻灯片的副本添加到指定章节的末尾。

### 返回

新幻灯片。



```python
def add_clone(self, source_slide, section):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |
| section | [`ISection`](/slides/python-net/zh/aspose.slides/isection) | 新幻灯片的章节。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
将指定幻灯片的副本添加到集合的末尾。

### 返回

新幻灯片。



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide) | 新幻灯片的布局幻灯片。 |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
将指定源幻灯片的副本添加到集合的末尾。  
将自动从指定的母版中选择合适的布局（合适的布局是与源幻灯片的布局具有相同类型或名称的布局）。如果没有合适的布局，则  
源幻灯片的布局将被克隆（如果 allowCloneMissingLayout 为 true）或抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。

### 返回

新幻灯片。



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要克隆的幻灯片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide) | 新幻灯片的母版幻灯片。 |
| allow_clone_missing_layout | **bool** | 如果在指定的母版中没有合适的布局，则 <br/><br/>            源幻灯片的布局将被克隆（如果 allowCloneMissingLayout 为 true）或 <br/><br/>            抛出 PptxEditException（如果 allowCloneMissingLayout 为 false）。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果在指定的母版中没有合适的布局且 <br/>            allowCloneMissingLayout 为 false，则抛出此异常。 |



### 另请参见
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide)
* 类 [`ISection`](/slides/python-net/zh/aspose.slides/isection)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`ISlideCollection`](/slides/python-net/zh/aspose.slides/islidecollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)