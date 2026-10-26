---
title: AddEffect()
second_title: Aspose.Slides for C++ API 参考
description: 在序列末尾添加新效果。
type: docs
weight: 144
url: /zh/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) 方法

在序列末尾添加新效果。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 对象 [IShape](../../../aspose.slides/ishape/) 用于添加效果 |
| effectType | [EffectType](../../effecttype/) | 动画效果的类型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 动画效果的子类型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的触发类型 [EffectTriggerType](../../effecttriggertype/) |

### 返回值

新效果对象 [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) 方法

在序列末尾为段落添加新的动画效果。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) 对象 [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | 动画效果的类型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 动画效果的子类型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的触发类型 [EffectTriggerType](../../effecttriggertype/) |

### 返回值

新效果对象 [IEffect](../../ieffect/)

## 备注

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// 选择要添加效果的段落
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// 为选定的段落添加 Fly 动画效果
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) 方法

在序列末尾为类别或系列添加新的图表动画效果。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Chart 对象 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | 动画效果的类型 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | 索引 **int32_t** |
| effectType | [EffectType](../../effecttype/) | 动画效果的类型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 动画效果的子类型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的触发类型 [EffectTriggerType](../../effecttriggertype/) |

### 返回值

新效果对象 [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) 方法

在序列末尾为类别或系列中的元素添加新的图表动画效果。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Chart 对象 [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | 动画效果的类型 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | 图表系列的索引 **int32_t** |
| categoriesIndex | **int32_t** | 类别的索引 **int32_t** |
| effectType | [EffectType](../../effecttype/) | 动画效果的类型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 动画效果的子类型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的触发类型 [EffectTriggerType](../../effecttriggertype/) |

### 返回值

新效果对象 [IEffect](../../ieffect/)

## 另请参见

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IEffect](../../ieffect/)
* 类 [IShape](../../../aspose.slides/ishape/)
* 类 [ISequence](../)
* 类 [IParagraph](../../../aspose.slides/iparagraph/)
* 类 [IChart](../../../aspose.slides.charts/ichart/)
* 命名空间 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)