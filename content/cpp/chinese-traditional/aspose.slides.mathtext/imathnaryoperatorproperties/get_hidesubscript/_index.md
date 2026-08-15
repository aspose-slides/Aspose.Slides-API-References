---
title: get_HideSubscript()
second_title: Aspose.Slides for C++ API 參考文件
description: 隱藏下標
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesubscript/
---
## IMathNaryOperatorProperties::get_HideSubscript() 方法


隱藏下標

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSubscript()=0
```

## 備註


範例： 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## 另請參閱

* 類別 [IMathNaryOperatorProperties](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)