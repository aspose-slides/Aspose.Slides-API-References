---
title: get_Base()
second_title: Aspose.Slides for C++ API 參考文件
description: Base 參數
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() 方法


Base 參數

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## 備註


範例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathNaryOperator](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)