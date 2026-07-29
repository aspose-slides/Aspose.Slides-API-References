---
title: get_Arguments()
second_title: Aspose.Slides för C++ API-referens
description: Mängden av element i arrayen
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() metod

Mängden av element i arrayen

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Anmärkningar

Exempel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElementCollection](../../imathelementcollection/)
* Klass [IMathArray](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)