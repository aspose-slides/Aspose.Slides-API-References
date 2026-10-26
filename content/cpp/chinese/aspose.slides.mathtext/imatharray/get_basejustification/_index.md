---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API 参考
description: "指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。默认值：Center"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() 方法

指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。默认值：Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 另见

* 枚举 [MathVerticalAlignment](../../mathverticalalignment/)
* 类 [IMathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)