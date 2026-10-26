---
title: AddEffect()
second_title: Aspose.Slides for C++ API 參考文件
description: 在序列末端新增效果。
type: docs
weight: 157
url: /zh-hant/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) 方法

在序列的末端新增效果。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 物件 [IShape](../../../aspose.slides/ishape/) 用於新增效果 |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 傳回值

新的效果物件 [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) 方法

在序列的末端為段落新增動畫效果。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) 物件 [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 傳回值

新的效果物件 [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) 方法

在序列的末端為類別或系列新增圖表動畫效果。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | 圖表物件 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | 動畫效果的類型 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | 索引 **int32_t** |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 傳回值

新的效果物件 [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) 方法

在序列的末端為類別或系列中的元素新增圖表動畫效果。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | 圖表物件 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | 動畫效果的類型 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | 圖表系列的索引 **int32_t** |
| categoriesIndex | **int32_t** | 類別的索引 **int32_t** |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 傳回值

新的效果物件 [IEffect](../../ieffect/)

## 備註

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// select paragraph to add effect
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// add Fly animation effect to selected paragraph
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## 另請參閱

* 列舉 [EffectType](../../effecttype/)
* 列舉 [EffectSubtype](../../effectsubtype/)
* 列舉 [EffectTriggerType](../../effecttriggertype/)
* 列舉 [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* 列舉 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IEffect](../../ieffect/)
* 類別 [IShape](../../../aspose.slides/ishape/)
* 類別 [Sequence](../)
* 類別 [IParagraph](../../../aspose.slides/iparagraph/)
* 類別 [IChart](../../../aspose.slides.charts/ichart/)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)