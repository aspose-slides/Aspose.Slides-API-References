---
title: Underbar()
second_title: Aspose.Slides for C++ API 参考
description: 在此元素底部设置一条下划线
type: docs
weight: 235
url: /zh/aspose.slides.mathtext/imathelement/underbar/
---
## IMathElement::Underbar() 方法


在此元素的底部设置一条下划线

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathElement::Underbar()=0
```


### 返回值

类型 [IMathBar](../../imathbar/) 的新实例
## 备注



示例：
```cpp
auto bar = System::MakeObject<MathematicalText>(u"x")->Underbar();
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBar](../../imathbar/)
* 类 [IMathElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)