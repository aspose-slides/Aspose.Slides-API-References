---
title: set_HideDegree()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏度数 当为 true 时，度数不显示，如 \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathradical/set_hidedegree/
---
## IMathRadical::set_HideDegree(bool) 方法


隐藏度数 当为 true 时，度数不显示，如 \\u221A\\uD835\\uDC65

```cpp
virtual void Aspose::Slides::MathText::IMathRadical::set_HideDegree(bool value)=0
```

## 备注


示例： 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
radical->set_HideDegree(true);
```

## 另见

* 类 [IMathRadical](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)