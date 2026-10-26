---
title: Enclose()
second_title: Aspose.Slides für C++ API-Referenz
description: Schließt ein mathematisches Element in Klammern ein
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() Methode

Schließt ein mathematisches Element in Klammern ein

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### Rückgabewert

Das mathematische Element vom Typ [IMathDelimiter](../../imathdelimiter/), das die Klammern enthält

## Anmerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) Methode

Schließt dieses Element in den angegebenen Zeichen ein, beispielsweise Klammern oder andere Zeichen als Rahmen

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char16_t | Anfangszeichen (in der Regel linke Klammer) |
| endingCharacter | char16_t | Endzeichen (in der Regel rechte Klammer) |

### Rückgabewert

Das mathematische Element vom Typ [IMathDelimiter](../../imathdelimiter/), das die angegebenen Zeichen als Rahmen enthält

## Anmerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [IMathElement](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)