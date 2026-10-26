---
title: get_Arguments()
second_title: Aspose.Slides für C++ API-Referenz
description: Ein oder mehrere mathematische Elemente, die durch Trennzeichen getrennt sind
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() Methode


Ein oder mehrere mathematische Elemente, die durch Trennzeichen getrennt sind

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Hinweise


Beispiel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElementCollection](../../imathelementcollection/)
* Klasse [MathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)