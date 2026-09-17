---
title: FontFallBackRule class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/fontfallbackrule/
---
## FontFallBackRule 类

表示字体回退规则

FontFallBackRule 类型公开以下成员：

## 构造函数

| Constructor | Description |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/__init__/#int-int-str) | 创建新实例。 |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | 创建新实例。 |

## 属性

| Property | Description |
| :- | :- |
| [`range_start_index`](/slides/python-net/zh/aspose.slides/fontfallbackrule/range_start_index/) | 获取连续 Unicode 范围的第一个索引。 |
| [`range_end_index`](/slides/python-net/zh/aspose.slides/fontfallbackrule/range_end_index/) | 获取连续 Unicode 范围的最后一个索引。 |
| [`count`](/slides/python-net/zh/aspose.slides/fontfallbackrule/count/) | 获取实际为该范围定义的字体数量。<br/>            只读 **int**. |

获取指定索引处的字体名称。  
            只读 [`IFontFallBackRule`](/slides/python-net/zh/aspose.slides/ifontfallbackrule).

## 索引器

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides/fontfallbackrule/__getitem__/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | 向 FallBack 字体列表添加新字体。 |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | 向 FallBack 字体列表添加新字体。 |
| [`to_array(self)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/to_array/#) | 创建并返回包含此规则所有 FallBack 字体的数组。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/to_array/#int-int) | 创建并返回列表中指定范围内所有 FallBack 字体的数组。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/clear/#) | 从列表中移除所有字体。 |
| [`remove(self, font_name)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/remove/#str) | 从列表中移除特定 FallBack 字体的第一次出现。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/remove_at/#int) | 从列表中指定索引位置移除 FallBack 字体。 |
| [`index_of(self, font_name)`](/slides/python-net/zh/aspose.slides/fontfallbackrule/index_of/#str) | 返回集合中指定规则的索引。 |

### 另请参阅
* 类 [`IFontFallBackRule`](/slides/python-net/zh/aspose.slides/ifontfallbackrule)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)