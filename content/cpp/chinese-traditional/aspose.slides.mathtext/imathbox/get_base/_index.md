---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考
description: Base 參數
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() 方法


Base 參數

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## 備註


範例：
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)