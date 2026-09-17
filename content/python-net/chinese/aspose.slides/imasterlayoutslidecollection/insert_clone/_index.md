---
title: insert_clone method
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
在集合的指定位置插入指定布局幻灯片的副本。

### 返回

已插入的幻灯片。

```python
def insert_clone(self, index, source_layout):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 新幻灯片的索引。 |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |

### 备注

新的布局将与此布局幻灯片集合的父母版幻灯片关联。因此，这相当于在 PowerPoint 中使用“Use Destination Theme”选项的复制/粘贴。

### 另见
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`IMasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)