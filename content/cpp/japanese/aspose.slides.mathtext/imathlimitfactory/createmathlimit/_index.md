---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API リファレンス
description: IMathLimit を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) メソッド

作成します [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 制限を適用するベース引数 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上限要素 |
| upperLimit | **bool** | リミットを上部に配置します |

### 戻り値

新しい数式リミット

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド

作成します [IMathLimit](../../imathlimit/)（下部にリミット）

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 制限を適用するベース引数 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上限要素 |

### 戻り値

新しい数式リミット

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathLimit](../../imathlimit/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathLimitFactory](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)