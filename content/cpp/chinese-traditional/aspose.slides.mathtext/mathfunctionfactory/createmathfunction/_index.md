---
title: CreateMathFunction()
second_title: Aspose.Slides for C++ API 參考
description: 建立數學函式
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


建立數學函式

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函式名稱的元素 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函式參數的元素 |

### 返回值

新的數學函式

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) method


建立數學函式

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | 函式名稱 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函式參數的元素 |

### 返回值

新的數學函式

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathFunction](../../imathfunction/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathFunctionFactory](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)