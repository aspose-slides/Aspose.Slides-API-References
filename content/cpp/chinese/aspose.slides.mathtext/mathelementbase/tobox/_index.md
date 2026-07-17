---
title: ToBox()
second_title: Aspose.Slides C++ API 参考
description: 将此元素放置在一个非可视的框中（逻辑分组），用于对方程式或其他数学文本实例的组件进行分组。例如，带框对象可以充当带或不带对齐点的运算符仿真器，充当换行点，或被分组以防止其中出现换行。
type: docs
weight: 261
url: /zh/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() 方法


将此元素放置在一个非可视的框中（逻辑分组），用于对方程式或其他数学文本实例的组成部分进行分组。一个带框的对象可以（例如）充当带或不带对齐点的运算符仿真器，充当换行点，或被分组以防止其中出现换行。

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### 返回值

逻辑盒，里面放置了此元素
## 备注



示例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBox](../../imathbox/)
* 类 [MathElementBase](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)