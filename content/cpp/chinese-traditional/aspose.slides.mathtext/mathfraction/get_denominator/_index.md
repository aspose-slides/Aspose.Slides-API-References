---
title: get_Denominator()
second_title: Aspose.Slides for C++ API 參考
description: 分母
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() 方法

分母

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
```

## 備註

範例:
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathFraction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)