---
title: get_Arguments()
second_title: Aspose.Slides för C++ API-referens
description: Mängden av objekt i arrayen
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() metod


Mängden av objekt i arrayen

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Anmärkningar


Exempel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElementCollection](../../imathelementcollection/)
* Klass [MathArray](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)