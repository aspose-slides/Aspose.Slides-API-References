---
title: get_Degree()
second_title: Aspose.Slides for C++ API リファレンス
description: Degree 引数
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() メソッド

Degree 引数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## 備考


例: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathRadical](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)