---
title: get_Arguments()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列の項目の集合
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() メソッド


配列の項目の集合

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## 備考


例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElementCollection](../../imathelementcollection/)
* クラス [MathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)