---
title: LayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/layoutslidecollection/
---
## LayoutSlideCollection 类

表示布局幻灯片集合的基类。

LayoutSlideCollection 类型公开以下成员：

返回指定索引的布局幻灯片。只读 [`LayoutSlide`](/slides/python-net/zh/aspose.slides/layoutslide)。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/layoutslidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/zh/aspose.slides/layoutslidecollection/get_by_type/#slidelayouttype) | 返回指定类型的第一个布局幻灯片。<br/>            要查找的布局幻灯片类型。[`LayoutSlide`](/slides/python-net/zh/aspose.slides/layoutslide)具有指定类型的布局幻灯片，如果未找到则返回 None。 |
| [`remove(self, value)`](/slides/python-net/zh/aspose.slides/layoutslidecollection/remove/#ilayoutslide) | 从集合中移除布局。 |
| [`remove_unused(self)`](/slides/python-net/zh/aspose.slides/layoutslidecollection/remove_unused/#) | 移除未使用的布局幻灯片（HasDependingSlides 为 false 的布局幻灯片）。 |


### 另请参阅
* 类 [`LayoutSlide`](/slides/python-net/zh/aspose.slides/layoutslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)