---
title: Function()
second_title: Aspose.Slides for C++ API 參考
description: 使用此實例作為函式名稱，取得帶有參數的函式
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) 方法

使用此實例作為函式名稱，取得帶有參數的函式

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 函式的參數 |

### 回傳值

新數學元素，類型為 [IMathFunction](../../imathfunction/)
## 備註



範例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) 方法

使用此實例作為函式名稱，取得帶有參數的函式

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | 函式的參數 |

### 回傳值

新數學元素，類型為 [IMathFunction](../../imathfunction/)
## 備註



範例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathFunction](../../imathfunction/)
* 類別 [IMathElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)