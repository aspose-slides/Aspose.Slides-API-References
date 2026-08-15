---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考文件
description: 套用重音的參數
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() 方法

套用重音的參數

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## 備註

範例：
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathAccent](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)