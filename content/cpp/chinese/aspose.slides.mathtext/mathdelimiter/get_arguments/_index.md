---
title: get_Arguments()
second_title: Aspose.Slides for C++ API 参考
description: 一个或多个由分隔符字符分隔的数学元素
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() 方法

一个或多个由分隔符字符分隔的数学元素

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## 备注

示例：
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElementCollection](../../imathelementcollection/)
* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)