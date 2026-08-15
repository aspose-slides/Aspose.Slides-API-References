---
title: CreateMathNaryOperator()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立 IMathNaryOperator
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathnaryoperatorfactory/createmathnaryoperator/
---
## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

建立 [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | 運算子符號 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用於套用運算子的基礎參數 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下限 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上限 |

### 回傳值

new [IMathNaryOperator](../../imathnaryoperator/)

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

建立 [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | 運算子符號 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用於套用運算子的基礎參數 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下限 |

### 回傳值

new [IMathNaryOperator](../../imathnaryoperator/)

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) method

建立 [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | 運算子符號 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用於套用運算子的基礎參數 |

### 回傳值

new [IMathNaryOperator](../../imathnaryoperator/)

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathNaryOperator](../../imathnaryoperator/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathNaryOperatorFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)