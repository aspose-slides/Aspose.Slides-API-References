---
title: Enclose()
second_title: Aspose.Slides für C++ API-Referenz
description: Schließt die Kindelemente dieses Blocks mit angegebenen Zeichen, wie Klammern oder anderen, als Rahmen ein und trennt sie mit einem Trennzeichen.
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) Methode

Schließt Kinderelemente dieses Blocks mit den angegebenen Zeichen, wie Klammern oder anderen, als Rahmen ein und trennt sie mit einem Trennzeichen

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char16_t | Anfangszeichen (normalerweise linke Klammer) |
| endingCharacter | char16_t | Abschlusszeichen (normalerweise rechte Klammer) |
| separatorCharacter | char16_t | Trennzeichen |

### Rückgabewert

Das mathematische Element vom Typ [IMathDelimiter](../../imathdelimiter/), das die angegebenen Zeichen als Rahmen und Trennzeichen enthält
## Bemerkungen

Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [IMathBlock](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)