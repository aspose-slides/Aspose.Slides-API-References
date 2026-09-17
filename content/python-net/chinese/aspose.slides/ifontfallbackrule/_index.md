---
title: IFontFallBackRule class
second_title: Aspose.Slides 用于 Python 通过 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ifontfallbackrule/
---
## IFontFallBackRule 类

表示字体回退规则

IFontFallBackRule 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`range_start_index`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/range_start_index/) | 获取连续 unicode 范围的起始索引。 |
| [`range_end_index`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/range_end_index/) | 获取连续 unicode 范围的结束索引。 |
| [`count`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/count/) | 获取实际为该范围定义的字体数量。 |

获取指定索引处的字体名称。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#str) | 向回退字体列表中添加新字体。 |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#liststr) | 向回退字体列表中添加新字体。 |
| [`to_array(self)`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/to_array/#) | 创建并返回此规则的所有回退字体数组。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/to_array/#int-int) | 创建并返回列表中指定范围的所有回退字体数组。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/clear/#) | 移除列表中的所有字体。 |
| [`remove(self, font_name)`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/remove/#str) | 从列表中移除首次出现的特定回退字体。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/remove_at/#int) | 移除列表中指定索引处的回退字体。 |
| [`index_of(self, font_name)`](/slides/python-net/zh/aspose.slides/ifontfallbackrule/index_of/#str) | 返回集合中指定规则的索引。 |


### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)