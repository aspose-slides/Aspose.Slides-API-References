---
title: get_Numerator()
second_title: Aspose.Slides for C++ API 參考文件
description: 分子
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() 方法

Numerator

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## 備註

範例：

```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathFraction](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)