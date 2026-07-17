---
title: get_Arguments()
second_title: Aspose.Slides for C++ API 参考
description: 数组的项集合
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() 方法

数组的项集合

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElementCollection](../../imathelementcollection/)
* 类 [IMathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)