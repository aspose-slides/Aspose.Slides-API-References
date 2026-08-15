---
title: set_HideDegree()
second_title: Aspose.Slides C++ API 參考
description: 隱藏指數 當為 true 時，指數不會顯示，如 \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathradical/set_hidedegree/
---
## IMathRadical::set_HideDegree(bool) 方法


隱藏指數 當為 true 時，指數不會顯示，如 \\u221A\\uD835\\uDC65

```cpp
virtual void Aspose::Slides::MathText::IMathRadical::set_HideDegree(bool value)=0
```

## 備註


Example: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
radical->set_HideDegree(true);
```

## 另見

* 類別 [IMathRadical](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)