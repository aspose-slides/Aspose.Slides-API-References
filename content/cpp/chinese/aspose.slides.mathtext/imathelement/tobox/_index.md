---
title: ToBox()
second_title: Aspose.Slides for C++ API 参考
description: 将此元素放置在一个非可视框（逻辑分组）中，用于对方程或其他数学文本实例的组件进行分组。一个被框住的对象可以（例如）充当带或不带对齐点的运算符仿真器，充当换行点，或被分组以防止在其中出现换行。
type: docs
weight: 274
url: /zh/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() 方法


将此元素放置在一个非可视框（逻辑分组）中，用于对方程或其他数学文本实例的组件进行分组。一个被框住的对象可以（例如）充当带或不带对齐点的运算符仿真器，充当换行点，或被分组以防止在其中出现换行。

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```


### 返回值

逻辑框，内部放置了此元素
## 备注



示例：
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBox](../../imathbox/)
* 类 [IMathElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)