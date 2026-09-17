---
title: Sequence class
second_title: Aspose.Slides 用于 Python 通过 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/sequence/
---
## Sequence 类

表示序列（效果的集合）。

Sequence 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`count`](/slides/python-net/zh/aspose.slides.animation/sequence/count/) | 返回序列中效果的数量。<br/>            只读 **int**. |
| [`trigger_shape`](/slides/python-net/zh/aspose.slides.animation/sequence/trigger_shape/) | 返回或设置形状目标用于 INTERACTIVE 序列。<br/>            如果序列不是交互式的则返回 None。<br/>            读/写 [`IShape`](/slides/python-net/zh/aspose.slides/ishape). |

返回指定索引处的效果。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.animation/sequence/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/zh/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | 在序列末尾添加新效果。 |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/zh/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | 在序列末尾为段落添加新的动画效果。 |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/zh/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | 在序列末尾为类别或系列添加新的图表动画效果。 |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/zh/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | 在序列末尾为类别或系列中的元素添加新的图表动画效果。 |
| [`remove(self, item)`](/slides/python-net/zh/aspose.slides.animation/sequence/remove/#ieffect) | 从集合中移除指定的效果。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides.animation/sequence/remove_at/#int) | 从集合中移除一个效果。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides.animation/sequence/clear/#) | 从集合中移除所有效果。 |
| [`remove_by_shape(self, shape)`](/slides/python-net/zh/aspose.slides.animation/sequence/remove_by_shape/#ishape) | 移除指定形状的效果。 |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/zh/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | 返回指定形状的效果数组。 |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/zh/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | 返回指定段落的效果数组。 |
| [`get_count(self, shape)`](/slides/python-net/zh/aspose.slides.animation/sequence/get_count/#ishape) | 返回指定形状的效果计数。 |

### 参见
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)