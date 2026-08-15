---
title: AddEffect()
second_title: Aspose.Slides for C++ API 參考文件
description: 在序列的末端新增效果。
type: docs
weight: 144
url: /zh-hant/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) 方法


在序列的末端加入新效果。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 物件 [IShape](../../../aspose.slides/ishape/) 用於新增效果 |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 回傳值

新的效果物件 [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) 方法


在序列的末端為段落加入新的動畫效果。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) 物件 [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 回傳值

新的效果物件 [IEffect](../../ieffect/)
## 備註




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// 選取要加入效果的段落
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// 為所選段落加入 Fly 動畫效果
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) 方法


在序列的末端加入新的圖表動畫效果（針對類別或系列）。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | 圖表 物件 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | 動畫效果的類型 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 回傳值

新的效果物件 [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) 方法


在序列的末端加入新的圖表動畫效果（針對類別或系列中的元素）。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | 圖表物件 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | 動畫效果的類型 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Index of chart series **int32_t** |
| categoriesIndex | **int32_t** | Index of category **int32_t** |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 回傳值

新的效果物件 [IEffect](../../ieffect/)

## 另請參閱

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [ISequence](../)
* Class [IParagraph](../../../aspose.slides/iparagraph/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)