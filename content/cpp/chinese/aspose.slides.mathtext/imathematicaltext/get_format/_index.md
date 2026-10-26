---
title: get_Format()
second_title: Aspose.Slides for C++ API 参考
description: 文本格式属性
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() 方法


文本格式属性

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## 备注


示例:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 类 [IMathematicalText](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)