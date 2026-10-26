---
title: get_HideDegree()
second_title: Aspose.Slides for C++ API 参考
description: 当 HideDegree 为 true 时，不显示度数，例如 \\u221A\\uD835\\uDC65
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathradical/get_hidedegree/
---
## MathRadical::get_HideDegree() 方法

当 HideDegree 为 true 时，不显示度数，例如 \\u221A\\uD835\\uDC65

```cpp
bool Aspose::Slides::MathText::MathRadical::get_HideDegree() override
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