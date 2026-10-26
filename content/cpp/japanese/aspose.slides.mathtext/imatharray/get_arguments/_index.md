---
title: get_Arguments()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列の項目の集合
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() メソッド

配列の項目の集合

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## 備考

例:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElementCollection](../../imathelementcollection/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)