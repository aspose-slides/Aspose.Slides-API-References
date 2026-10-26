---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection 类

表示演示文稿中所有布局幻灯片的集合。  
扩展 LayoutSlideCollection 类，提供在合并各个母版布局幻灯片集合的上下文中添加/克隆布局幻灯片的方法。

**继承:**[`GlobalLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/zh/aspose.slides/layoutslidecollection)

GlobalLayoutSlideCollection 类型公开以下成员：

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | 向演示文稿中添加指定布局幻灯片的副本。 |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | 向演示文稿中添加指定布局幻灯片的副本。 |
| [`get_by_type(self, type)`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | 返回指定类型的第一个布局幻灯片。<br/>            要查找的布局幻灯片类型。[`LayoutSlide`](/slides/python-net/zh/aspose.slides/layoutslide) 具有指定类型的布局幻灯片，如果未找到则返回 None。 |
| [`remove(self, value)`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | 从集合中移除布局。 |
| [`remove_unused(self)`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection/remove_unused/#) | 移除未使用的布局幻灯片（HasDependingSlides 为 false 的布局幻灯片）。 |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | 向演示文稿中添加新的布局幻灯片。 |

### 另见
* 类 [`GlobalLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection)
* 类 [`LayoutSlideCollection`](/slides/python-net/zh/aspose.slides/layoutslidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)