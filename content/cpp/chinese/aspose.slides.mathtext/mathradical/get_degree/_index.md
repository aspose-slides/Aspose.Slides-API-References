---
title: get_Degree()
second_title: Aspose.Slides for C++ API 参考
description: Degree 参数
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() 方法


Degree 参数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## 备注


示例：
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathRadical](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)