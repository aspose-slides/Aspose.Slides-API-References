---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API リファレンス
description: IMathLimit を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) method

作成 [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | リミットを適用する基底引数 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | リミット要素 |
| upperLimit | **bool** | リミットの上部配置を設定 |

### 戻り値

新しい数式リミット

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

作成 [IMathLimit](../../imathlimit/)（下部にリミット）

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | リミットを適用する基底引数 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | リミット要素 |

### 戻り値

新しい数式リミット

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathLimit](../../imathlimit/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathLimitFactory](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)