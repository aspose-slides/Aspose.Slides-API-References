---
title: ISequence class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/isequence/
---
## ISequence 类

表示序列（效果的集合）。

ISequence 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`count`](/slides/python-net/zh/aspose.slides.animation/isequence/count/) | 返回序列中效果的数量。<br/>            只读 **int**。 |
| [`trigger_shape`](/slides/python-net/zh/aspose.slides.animation/isequence/trigger_shape/) | 返回或设置 INTERACTIVE 序列的形状目标。<br/>            如果序列不是交互式的则返回 None。<br/>            可读写 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |

返回在指定索引处的效果。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.animation/isequence/__getitem__/) | 索引 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/zh/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | 在序列末尾添加新效果。 |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/zh/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | 在序列末尾添加新的段落动画效果。 |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/zh/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | 在序列末尾添加新的图表动画效果（针对类别或系列）。 |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/zh/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | 在序列末尾添加新的图表动画效果（针对类别或系列中的元素）。 |
| [`remove(self, item)`](/slides/python-net/zh/aspose.slides.animation/isequence/remove/#ieffect) | 从集合中移除指定的效果。 |
| [`remove_at(self, index)`](/slides/python-net/zh/aspose.slides.animation/isequence/remove_at/#int) | 从集合中移除一个效果。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides.animation/isequence/clear/#) | 从集合中移除所有效果。 |
| [`remove_by_shape(self, shape)`](/slides/python-net/zh/aspose.slides.animation/isequence/remove_by_shape/#ishape) | 移除指定形状的效果。 |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/zh/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | 返回指定形状的效果数组。 |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/zh/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | 返回指定段落的效果数组。 |
| [`get_count(self, shape)`](/slides/python-net/zh/aspose.slides.animation/isequence/get_count/#ishape) | 返回指定形状的效果计数。 |


### 另请参见
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)