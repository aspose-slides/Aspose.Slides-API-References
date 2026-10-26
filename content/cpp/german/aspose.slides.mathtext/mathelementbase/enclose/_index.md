---
title: Enclose()
second_title: Aspose.Slides für C++ API Referenz
description: Umschließt ein mathematisches Element in Klammern
type: docs
weight: 27
url: /de/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() Methode


Umschließt ein mathematisches Element in Klammern

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Rückgabewert

Das mathematische Element vom Typ [IMathDelimiter](../../imathdelimiter/), das die Klammern enthält
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) Methode


Umschließt ein mathematisches Element in angegebenen Zeichen, wie z. B. Klammern oder anderen Zeichen als Rahmen

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char16_t | Anfangszeichen (normalerweise linke Klammer) |
| endingCharacter | char16_t | Endzeichen (normalerweise rechte Klammer) |

### Rückgabewert

Das mathematische Element vom Typ [IMathDelimiter](../../imathdelimiter/), das die angegebenen Zeichen als Rahmen enthält
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [MathElementBase](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)