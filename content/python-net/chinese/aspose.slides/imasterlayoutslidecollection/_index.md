---
title: IMasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/imasterlayoutslidecollection/
---
## IMasterLayoutSlideCollection 类

表示已定义母版幻灯片的所有布局幻灯片的集合。  
扩展 ILayoutSlideCollection 接口，提供在母版布局幻灯片各自集合的上下文中添加/插入/删除/克隆布局幻灯片的方法。

IMasterLayoutSlideCollection 类型公开以下成员：

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/add_clone/#ilayoutslide) | 将指定布局幻灯片的副本添加到集合的末尾。 |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/insert_clone/#int-ilayoutslide) | 将指定布局幻灯片的副本插入到集合的指定位置。 |
| [`add(self, layout_type, layout_name)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/add/#slidelayouttype-str) | 将新布局幻灯片添加到集合的末尾。 |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/insert/#int-slidelayouttype-str) | 将新布局幻灯片插入到集合的指定位置。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/remove_at/#int) | 删除集合中指定索引处的元素。 |
| [`reorder(self, index, layout_slide)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/reorder/#int-ilayoutslide) | 将布局幻灯片从集合中移动到指定位置。 |
| [`get_by_type(self, type)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/get_by_type/#slidelayouttype) |  |
| [`remove(self, value)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/remove/#ilayoutslide) |  |
| [`remove_unused(self)`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection/remove_unused/#) |  |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)