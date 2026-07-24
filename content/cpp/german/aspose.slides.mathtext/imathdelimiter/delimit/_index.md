---
title: Delimit()
second_title: Aspose.Slides für C++ API-Referenz
description: Begrenzt Argumente mit dem angegebenen Trennzeichen
type: docs
weight: 144
url: /de/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) Methode

Begrenzt Argumente mithilfe des angegebenen Trennzeichens

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | char16_t | Trennzeichen |

### Rückgabewert

Dieses Objekt nach Anwendung des Trennzeichens
## Anmerkungen



Beispiel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)