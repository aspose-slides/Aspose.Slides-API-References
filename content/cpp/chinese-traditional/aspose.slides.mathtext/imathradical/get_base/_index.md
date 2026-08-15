---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考
description: Base 參數
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() 方法


Base 參數

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## 備註


範例:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
auto baseElem = radical->get_Base();
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathRadical](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)