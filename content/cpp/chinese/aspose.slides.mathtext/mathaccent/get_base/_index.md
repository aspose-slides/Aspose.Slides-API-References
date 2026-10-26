---
title: get_Base()
second_title: Aspose.Slides C++ API 参考
description: 重音所应用的参数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() 方法


重音被应用的参数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## 备注


示例:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathAccent](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)