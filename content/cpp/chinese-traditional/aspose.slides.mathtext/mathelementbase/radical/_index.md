---
title: Radical()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定給定次方的數學根號，使用指定的參數。
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) 方法

指定給定次方的數學根號，使用指定的參數。

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Radical 的參數 |

### 返回值

新建立的 [IMathRadical](../../imathradical/) 實例
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) 方法

指定給定次方的數學根號，使用指定的參數。

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Radical 的參數 |

### 返回值

新建立的 [IMathRadical](../../imathradical/) 實例
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathRadical](../../imathradical/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)