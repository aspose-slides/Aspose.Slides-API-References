---
title: CreateMathFunction()
second_title: Aspose.Slides for C++ API 參考
description: 建立數學函式
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法

建立數學函式

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函式名稱的元素 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函式參數的元素 |

### 返回值

新的數學函式

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) 方法

建立數學函式

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | 函式名稱 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函式參數的元素 |

### 返回值

新的數學函式

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathFunction](../../imathfunction/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathFunctionFactory](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)