---
title: get_Format()
second_title: Aspose.Slides for C++ API 参考
description: 文本格式属性
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathematicaltext/get_format/
---
## MathematicalText::get_Format() 方法


文本格式属性

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::MathematicalText::get_Format() override
```

## 备注


示例：
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 类 [MathematicalText](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)