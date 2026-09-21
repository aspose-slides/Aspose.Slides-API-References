---
title: Sequence class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.animation/sequence/
---
## Sequence 類別

表示序列（效果的集合）。

Sequence 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/count/) | 返回序列中效果的數量。<br/>            只讀 **int**. |
| [`trigger_shape`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/trigger_shape/) | 返回或設定 INTERACTIVE 序列的形狀目標。<br/>            如果序列不是互動的，則返回 None。<br/>            可讀寫 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape). |

在指定索引返回一個效果。

## 索引子

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/__getitem__/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | 將新效果新增至序列的末端。 |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | 將段落的新動畫效果新增至序列的末端。 |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | 將針對類別或系列的新圖表動畫效果新增至序列的末端。 |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | 將針對類別或系列中元素的新圖表動畫效果新增至序列的末端。 |
| [`remove(self, item)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/remove/#ieffect) | 從集合中移除指定的效果。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/remove_at/#int) | 從集合中移除一個效果。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/clear/#) | 從集合中移除所有效果。 |
| [`remove_by_shape(self, shape)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/remove_by_shape/#ishape) | 移除指定形狀的效果。 |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | 返回指定形狀的效果陣列。 |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | 返回指定段落的效果陣列。 |
| [`get_count(self, shape)`](/slides/python-net/zh-hant/aspose.slides.animation/sequence/get_count/#ishape) | 返回指定形狀的效果數量。 |

### 另請參見
* 模組 [`aspose.slides.animation`](/slides/python-net/zh-hant/aspose.slides.animation)
* 程式庫 [`Aspose.Slides`](/slides/python-net)