---
title: get_Base()
second_title: Aspose.Slides for C++ API 参考
description: 重音所应用的参数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() 方法


重音所应用的参数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
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
* 类 [IMathAccent](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)