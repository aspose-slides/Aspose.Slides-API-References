---
title: CreateMathNaryOperator()
second_title: Aspose.Slides for C++ API リファレンス
description: IMathNaryOperator を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathnaryoperatorfactory/createmathnaryoperator/
---
## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド

[IMathNaryOperator](../../imathnaryoperator/) を作成します

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit |

### 戻り値

[IMathNaryOperator](../../imathnaryoperator/) を新規作成

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド

[IMathNaryOperator](../../imathnaryoperator/) を作成します

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |

### 戻り値

[IMathNaryOperator](../../imathnaryoperator/) を新規作成

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) メソッド

[IMathNaryOperator](../../imathnaryoperator/) を作成します

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |

### 戻り値

[IMathNaryOperator](../../imathnaryoperator/) を新規作成

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathNaryOperator](../../imathnaryoperator/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathNaryOperatorFactory](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)