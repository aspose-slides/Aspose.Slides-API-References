---
title: ToMathArray()
second_title: Aspose.Slides for C++ API 参考
description: 将其放入垂直数组
type: docs
weight: 170
url: /zh/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() 方法


将内容放入垂直数组中

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### 返回值

类型 [IMathArray](../../imatharray/) 的新实例
## 备注



示例: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathArray](../../imatharray/)
* 类 [MathElementBase](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)