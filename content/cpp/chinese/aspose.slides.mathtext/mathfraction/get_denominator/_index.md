---
title: get_Denominator()
second_title: Aspose.Slides for C++ API 参考
description: 分母
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() 方法

分母

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
```

## 备注

示例：
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathFraction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)