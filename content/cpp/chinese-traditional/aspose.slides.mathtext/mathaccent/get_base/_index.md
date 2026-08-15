---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考
description: 套用重音的參數
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() 方法


套用重音的參數

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## 備註


範例：
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathAccent](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)