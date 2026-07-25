---
title: get_Base()
second_title: Aspose.Slides for C++ API リファレンス
description: Base 引数
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathgroupingcharacter/get_base/
---
## IMathGroupingCharacter::get_Base() メソッド

Base 引数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathGroupingCharacter::get_Base()=0
```

## 備考

例:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)