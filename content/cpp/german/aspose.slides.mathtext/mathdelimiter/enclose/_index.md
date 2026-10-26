---
title: Enclose()
second_title: Aspose.Slides für C++ API-Referenz
description: Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein
type: docs
weight: 170
url: /de/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) Methode

Enschließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char16_t | Anfangszeichen (üblicherweise linke Klammer) |
| endingCharacter | char16_t | Endzeichen (üblicherweise rechte Klammer) |

### Rückgabewert

Wenn *beginningCharacter* und *endingCharacter* null sind, werden die entsprechenden Eigenschaften nur zugewiesen und es wird kein neues Objekt erstellt (liefert diese Instanz zurück). Andernfalls wird ein neues Mathe-Element vom Typ Delimiter zurückgegeben, das die angegebenen Zeichen als Rahmen enthält und diese Instanz von [MathDelimiter](../) darin gerahmt ist.

## Bemerkungen

Beispiel: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [MathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)