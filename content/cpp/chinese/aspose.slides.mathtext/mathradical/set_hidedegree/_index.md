---
title: set_HideDegree()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏指数 当为 true 时，指数不显示，例如 \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathradical/set_hidedegree/
---
## MathRadical::set_HideDegree(bool) 方法

隐藏指数 当为 true 时，指数不显示，例如 \\u221A\\uD835\\uDC65

```cpp
void Aspose::Slides::MathText::MathRadical::set_HideDegree(bool value) override
```

## 备注

示例：
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
radical->set_HideDegree(true);
```

## 另见

* 类 [MathRadical](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)