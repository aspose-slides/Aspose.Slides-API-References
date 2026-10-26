---
title: get_HideDegree()
second_title: Aspose.Slides for C++ API 參考
description: 隱藏次方 為 true 時，次方不會顯示，如 \\u221A\\uD835\\uDC65
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathradical/get_hidedegree/
---
## IMathRadical::get_HideDegree() 方法

隱藏次方 為 true 時，次方不會顯示，如 \\u221A\\uD835\\uDC65

```cpp
virtual bool Aspose::Slides::MathText::IMathRadical::get_HideDegree()=0
```

## 備註

範例：
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
radical->set_HideDegree(true);
```

## 另見

* 類別 [IMathRadical](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)