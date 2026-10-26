---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection 类

表示已定义母版幻灯片的所有布局幻灯片的集合。  
扩展 LayoutSlideCollection 类，提供在母版布局幻灯片的各个集合上下文中添加/插入/移除/克隆/重新排序布局幻灯片的方法。

**继承:**[`MasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/zh/aspose.slides/layoutslidecollection)

MasterLayoutSlideCollection 类型公开以下成员：

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | 返回具有指定类型的第一个布局幻灯片。<br/>            要查找的布局幻灯片类型。[`LayoutSlide`](/slides/python-net/zh/aspose.slides/layoutslide) 如果未找到布局，则返回具有指定类型的对象或 None。 |
| [`remove(self, value)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | 从集合中移除布局。 |
| [`remove_unused(self)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/remove_unused/#) | 移除未使用的布局幻灯片（HasDependingSlides 为 false 的布局幻灯片）。 |
| [`add_clone(self, source_layout)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | 将指定布局幻灯片的副本添加到集合的末尾。 |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | 在集合的指定位置插入指定布局幻灯片的副本。 |
| [`add(self, layout_type, layout_name)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | 在集合的末尾添加新的布局幻灯片。 |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | 在集合的指定位置插入新的布局幻灯片。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/remove_at/#int) | 移除集合中指定索引处的元素。 |
| [`reorder(self, index, layout_slide)`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | 将布局幻灯片从集合移动到指定位置。 |

### 另请参见
* 类 [`LayoutSlideCollection`](/slides/python-net/zh/aspose.slides/layoutslidecollection)
* 类 [`MasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)