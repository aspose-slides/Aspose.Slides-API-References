---
title: ToMathArray()
second_title: Aspose.Slides for C++ API 参考
description: 放入一个垂直数组
type: docs
weight: 183
url: /zh/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() method

放入一个垂直数组

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```

### 返回值

新实例，类型为 [IMathArray](../../imatharray/)

## 备注

示例：
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathArray](../../imatharray/)
* 类 [IMathElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)