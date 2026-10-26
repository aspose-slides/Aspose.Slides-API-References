---
title: AddEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスの末尾に新しいエフェクトを追加します。
type: docs
weight: 157
url: /ja/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) メソッド

シーケンスの末尾に新しいエフェクトを追加します。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) オブジェクト [IShape](../../../aspose.slides/ishape/) をエフェクトの追加用に |
| effectType | [EffectType](../../effecttype/) | アニメーション効果 [EffectType](../../effecttype/) のタイプ |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果 [EffectSubtype](../../effectsubtype/) のサブタイプ |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | エフェクト [EffectTriggerType](../../effecttriggertype/) のトリガータイプ |

### 戻り値

新しいエフェクトオブジェクト [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) メソッド

シーケンスの末尾に段落用の新しいアニメーション効果を追加します。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) オブジェクト [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | アニメーション効果 [EffectType](../../effecttype/) のタイプ |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果 [EffectSubtype](../../effectsubtype/) のサブタイプ |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | エフェクト [EffectTriggerType](../../effecttriggertype/) のトリガータイプ |

### 戻り値

新しいエフェクトオブジェクト [IEffect](../../ieffect/)

## 備考

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// エフェクトを追加する段落を選択
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// 選択した段落に Fly アニメーションエフェクトを追加
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) メソッド

シーケンスの末尾にカテゴリまたは系列の新しいチャートアニメーション効果を追加します。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | チャートオブジェクト [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | アニメーション効果 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) のタイプ |
| index | **int32_t** | インデックス **int32_t** |
| effectType | [EffectType](../../effecttype/) | アニメーション効果 [EffectType](../../effecttype/) のタイプ |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果 [EffectSubtype](../../effectsubtype/) のサブタイプ |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | エフェクト [EffectTriggerType](../../effecttriggertype/) のトリガータイプ |

### 戻り値

新しいエフェクトオブジェクト [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) メソッド

シーケンスの末尾にカテゴリまたは系列の要素向けの新しいチャートアニメーション効果を追加します。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | チャートオブジェクト [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | アニメーション効果 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) のタイプ |
| seriesIndex | **int32_t** | チャート系列のインデックス **int32_t** |
| categoriesIndex | **int32_t** | カテゴリのインデックス **int32_t** |
| effectType | [EffectType](../../effecttype/) | アニメーション効果 [EffectType](../../effecttype/) のタイプ |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果 [EffectSubtype](../../effectsubtype/) のサブタイプ |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | エフェクト [EffectTriggerType](../../effecttriggertype/) のトリガータイプ |

### 戻り値

新しいエフェクトオブジェクト [IEffect](../../ieffect/)

## 参照

* 列挙型 [EffectType](../../effecttype/)
* 列挙型 [EffectSubtype](../../effectsubtype/)
* 列挙型 [EffectTriggerType](../../effecttriggertype/)
* 列挙型 [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* 列挙型 [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IEffect](../../ieffect/)
* クラス [IShape](../../../aspose.slides/ishape/)
* クラス [Sequence](../)
* クラス [IParagraph](../../../aspose.slides/iparagraph/)
* クラス [IChart](../../../aspose.slides.charts/ichart/)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)