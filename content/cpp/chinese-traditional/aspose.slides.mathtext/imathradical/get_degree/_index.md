---
title: get_Degree()
second_title: Aspose.Slides for C++ API 參考文件
description: Degree 參數
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() 方法

Degree 參數

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## 備註

範例：
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
auto degreeElem = radical->get_Degree();
```

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathRadical](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)