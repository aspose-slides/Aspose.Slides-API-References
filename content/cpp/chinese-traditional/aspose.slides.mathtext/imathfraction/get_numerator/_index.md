---
title: get_Numerator()
second_title: Aspose.Slides C++ API 參考
description: 分子
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() 方法


Numerator

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
```

## 備註


範例：
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathFraction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)