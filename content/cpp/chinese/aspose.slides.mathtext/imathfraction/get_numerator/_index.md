---
title: get_Numerator()
second_title: Aspose.Slides C++ API 参考
description: 分子
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() method

分子

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
```

## 备注

示例：
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathFraction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)