---
title: get_HideSubscript()
second_title: Aspose.Slides C++ API 參考文件
description: 隱藏下標
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() 方法


隱藏下標

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## 備註


範例： 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## 另請參閱

* 類別 [MathNaryOperator](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)