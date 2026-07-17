---
title: Overbar()
second_title: Aspose.Slides for C++ API 参考
description: 在此元素的顶部设置一条横线
type: docs
weight: 209
url: /zh/aspose.slides.mathtext/mathelementbase/overbar/
---
## MathElementBase::Overbar() 方法


在此元素的顶部设置一条横线

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathElementBase::Overbar() override
```


### 返回值

类型 [IMathBar](../../imathbar/) 的新实例
## 备注



示例： 
```cpp
auto bar = System::MakeObject<MathematicalText>(u"x")->Overbar();
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBar](../../imathbar/)
* 类 [MathElementBase](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)