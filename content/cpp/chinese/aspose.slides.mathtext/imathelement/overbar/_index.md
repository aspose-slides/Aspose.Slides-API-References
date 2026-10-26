---
title: Overbar()
second_title: Aspose.Slides for C++ API 参考
description: 在此元素的顶部设置一条横线
type: docs
weight: 222
url: /zh/aspose.slides.mathtext/imathelement/overbar/
---
## IMathElement::Overbar() 方法


在此元素的顶部设置一条横线

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathElement::Overbar()=0
```


### 返回值

New instance of type [IMathBar](../../imathbar/)
## 备注



示例:
```cpp
auto bar = System::MakeObject<MathematicalText>(u"x")->Overbar();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBar](../../imathbar/)
* 类 [IMathElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)