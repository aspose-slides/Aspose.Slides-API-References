---
title: get_Base()
second_title: Aspose.Slides C++ API 参考
description: Base 参数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() 方法


Base 参数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## 备注


示例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)