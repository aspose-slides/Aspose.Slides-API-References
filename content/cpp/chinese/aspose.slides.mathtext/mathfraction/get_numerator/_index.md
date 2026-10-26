---
title: get_Numerator()
second_title: Aspose.Slides for C++ API 参考
description: 分子
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() 方法


分子

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## 备注


示例: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathFraction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)