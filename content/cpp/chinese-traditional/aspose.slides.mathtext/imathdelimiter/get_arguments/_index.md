---
title: get_Arguments()
second_title: Aspose.Slides for C++ API 參考
description: 一個或多個以分隔符字符分隔的數學元素
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() 方法


一個或多個以分隔符字符分隔的數學元素

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## 備註


範例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElementCollection](../../imathelementcollection/)
* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)