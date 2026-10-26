---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
向集合末尾添加指定布局幻灯片的副本。

### 返回值

已添加的幻灯片。

```python
def add_clone(self, source_layout):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |

### 备注

1) 新布局将与此布局幻灯片集合的父母版幻灯片关联。  
   因此这相当于在 PowerPoint 中使用 “Use Destination Theme” 选项的复制/粘贴。  
2) 此方法的类似方法是 **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**，通过 [`IPresentation.layout_slides`](/slides/python-net/zh/aspose.slides/ipresentation/layout_slides) 属性访问。

### 另请参阅
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`MasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)