---
title: get_Degree()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: Degree 引数
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() メソッド


Degree 引数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## 備考


例: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
auto degreeElem = radical->get_Degree();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathRadical](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)