---
title: set_HideDegree()
second_title: Aspose.Slides for C++ API 參考
description: 當 Hide degree 為 true 時，次方不會顯示，例如 \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathradical/set_hidedegree/
---
## MathRadical::set_HideDegree(bool) 方法

當 Hide degree 為 true 時，次方不會顯示，例如 \\u221A\\uD835\\uDC65

```cpp
void Aspose::Slides::MathText::MathRadical::set_HideDegree(bool value) override
```

## 備註

範例：
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
radical->set_HideDegree(true);
```

## 另見

* 類別 [MathRadical](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)