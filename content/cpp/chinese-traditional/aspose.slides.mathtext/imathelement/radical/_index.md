---
title: Radical()
second_title: Aspose.Slides for C++ API 參考
description: 指定從指定參數中取得給定次方的數學根。
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) 方法

指定給定次方的數學根，取自指定的參數。

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Radical 的參數 |

### 返回值

新實例類型 [IMathRadical](../../imathradical/)
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) 方法

指定給定次方的數學根，取自指定的參數。

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Radical 的參數 |

### 返回值

新實例類型 [IMathRadical](../../imathradical/)
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRadical](../../imathradical/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)