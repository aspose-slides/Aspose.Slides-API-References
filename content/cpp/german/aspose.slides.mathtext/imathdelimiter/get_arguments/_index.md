---
title: get_Arguments()
second_title: Aspose.Slides für C++ API-Referenz
description: Ein oder mehrere mathematische Elemente, die durch Trennzeichen getrennt sind
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() Methode

Ein oder mehrere mathematische Elemente, die durch Trennzeichenzeichen getrennt sind

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Anmerkungen

Beispiel:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElementCollection](../../imathelementcollection/)
* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)