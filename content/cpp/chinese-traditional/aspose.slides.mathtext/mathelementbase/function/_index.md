---
title: Function()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用此實例作為函式名稱，接受一個參數的函式
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) 方法

使用此實例作為函式名稱，接受一個參數的函式

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 函式的參數 |

### 返回值

新數學元素類型 [IMathFunction](../../imathfunction/)

## 備註



範例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) 方法

使用此實例作為函式名稱，接受一個參數的函式

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | 函式的參數 |

### 返回值

新數學元素類型 [IMathFunction](../../imathfunction/)

## 備註



範例： 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)