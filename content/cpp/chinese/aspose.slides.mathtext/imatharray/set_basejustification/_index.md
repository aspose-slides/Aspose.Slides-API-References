---
title: set_BaseJustification()
second_title: Aspose.Slides C++ API 参考
description: "指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。默认值：Center"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) 方法


指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。默认值：Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## 备注


示例： 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 另请参见

* 枚举 [MathVerticalAlignment](../../mathverticalalignment/)
* 类 [IMathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)