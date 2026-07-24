---
title: Enclose()
second_title: Aspose.Slides für C++ API-Referenz
description: Umfasst Kind-Elemente dieses Blocks mit angegebenen Zeichen, wie Klammern oder anderen Zeichen, als Rahmen
type: docs
weight: 222
url: /de/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) Methode

Umfasst Kind-Elemente dieses Blocks mit angegebenen Zeichen, wie Klammern oder anderen Zeichen, als Rahmen

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginnendes Zeichen (normalerweise linke Klammer) |
| endingCharacter | char16_t | Endendes Zeichen (normalerweise rechte Klammer) |

### Rückgabewert

Das mathematische Element vom Typ [IMathDelimiter](../../imathdelimiter/), das die angegebenen Zeichen als Rahmen enthält
## Anmerkungen



Beispiel: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) Methode

Umfasst Kind-Elemente dieses Blocks mit angegebenen Zeichen, wie Klammern oder anderen, als Rahmen und trennt sie mit einem Trennzeichen

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginnendes Zeichen (normalerweise linke Klammer) |
| endingCharacter | char16_t | Endendes Zeichen (normalerweise rechte Klammer) |
| separatorCharacter | char16_t | Trennzeichen |

### Rückgabewert

Das mathematische Element vom Typ [IMathDelimiter](../../imathdelimiter/), das die angegebenen Zeichen als Rahmen und Trennzeichen enthält
## Anmerkungen



Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [MathBlock](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)