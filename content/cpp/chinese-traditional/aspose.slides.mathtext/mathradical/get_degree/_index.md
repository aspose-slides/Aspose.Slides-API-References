---
title: get_Degree()
second_title: Aspose.Slides for C++ API 參考手冊
description: Degree 參數
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() 方法

Degree 參數

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## 備註

範例：
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathRadical](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)