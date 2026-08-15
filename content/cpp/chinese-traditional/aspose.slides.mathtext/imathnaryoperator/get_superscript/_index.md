---
title: get_Superscript()
second_title: Aspose.Slides C++ API 參考
description: 指定一個上標參數，例如在積分的情況下，設定上限
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() 方法

指定一個上標參數，例如在積分的情況下，設定上限

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## 備註

範例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathNaryOperator](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)