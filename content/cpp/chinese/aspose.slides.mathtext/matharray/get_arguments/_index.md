---
title: get_Arguments()
second_title: Aspose.Slides C++ API 参考
description: 数组的项集合
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() 方法

数组的项集合

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElementCollection](../../imathelementcollection/)
* 类 [MathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)