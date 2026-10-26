---
title: get_Degree()
second_title: Aspose.Slides C++ API 参考
description: Degree 参数
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() 方法

Degree 参数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## 备注

示例:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
auto degreeElem = radical->get_Degree();
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathRadical](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)