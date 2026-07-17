---
title: get_Denominator()
second_title: Aspose.Slides C++ API 参考
description: 分母
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() 方法

分母

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## 备注

示例: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathFraction](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)