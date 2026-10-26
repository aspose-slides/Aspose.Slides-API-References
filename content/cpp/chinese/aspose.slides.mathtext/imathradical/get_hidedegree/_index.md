---
title: get_HideDegree()
second_title: Aspose.Slides C++ API 参考
description: 当 Hide degree 为 true 时，指数不显示，例如 \\u221A\\uD835\\uDC65
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathradical/get_hidedegree/
---
## IMathRadical::get_HideDegree() 方法


当 HideDegree 为 true 时，不显示指数，例如 \\u221A\\uD835\\uDC65

```cpp
virtual bool Aspose::Slides::MathText::IMathRadical::get_HideDegree()=0
```

## 备注


示例：
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
radical->set_HideDegree(true);
```

## 另请参见

* 类 [IMathRadical](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)