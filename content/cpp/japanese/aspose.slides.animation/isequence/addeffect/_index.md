---
title: AddEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスの末尾に新しいエフェクトを追加します。
type: docs
weight: 144
url: /ja/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) メソッド


シーケンスの末尾に新しいエフェクトを追加します。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) オブジェクト [IShape](../../../aspose.slides/ishape/) エフェクトを追加するための |
| effectType | [EffectType](../../effecttype/) | アニメーション効果のタイプ [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果のサブタイプ [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | エフェクトのトリガータイプ [EffectTriggerType](../../effecttriggertype/) |

### 戻り値

新しいエフェクトオブジェクト [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) メソッド


シーケンスの末尾に段落用の新しいアニメーションエフェクトを追加します。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) オブジェクト [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | アニメーション効果のタイプ [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果のサブタイプ [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | エフェクトのトリガータイプ [EffectTriggerType](../../effecttriggertype/) |

### 戻り値

新しいエフェクトオブジェクト [IEffect](../../ieffect/)
## 備考




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// エフェクトを追加する段落を選択
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// 選択した段落に Fly アニメーションエフェクトを追加
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) メソッド


シーケンスの末尾にカテゴリまたはシリーズ用の新しいチャートアニメーションエフェクトを追加します。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | チャートオブジェクト [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | アニメーション効果のタイプ [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | インデックス **int32_t** |
| effectType | [EffectType](../../effecttype/) | アニメーション効果のタイプ [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果のサブタイプ [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | エフェクトのトリガータイプ [EffectTriggerType](../../effecttriggertype/) |

### 戻り値

新しいエフェクトオブジェクト [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) メソッド


シーケンスの末尾にカテゴリまたはシリーズ内の要素用の新しいチャートアニメーションエフェクトを追加します。

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | チャートオブジェクト [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | アニメーション効果のタイプ [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | チャートシリーズのインデックス **int32_t** |
| categoriesIndex | **int32_t** | カテゴリのインデックス **int32_t** |
| effectType | [EffectType](../../effecttype/) | アニメーション効果のタイプ [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果のサブタイプ [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | エフェクトのトリガータイプ [EffectTriggerType](../../effecttriggertype/) |

### 戻り値

新しいエフェクトオブジェクト [IEffect](../../ieffect/)

## 関連項目

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