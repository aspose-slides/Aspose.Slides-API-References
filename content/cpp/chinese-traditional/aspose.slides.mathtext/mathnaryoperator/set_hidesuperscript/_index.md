---
title: set_HideSuperscript()
second_title: Aspose.Slides C++ API 參考
description: 隱藏上標
type: docs
weight: 157
url: /zh-hant/aspose.slides.mathtext/mathnaryoperator/set_hidesuperscript/
---
## MathNaryOperator::set_HideSuperscript(bool) 方法


隱藏上標

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSuperscript(bool value) override
```

## 備註


範例： 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## 另見

* 類別 [MathNaryOperator](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)