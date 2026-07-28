---
title: Enclose()
second_title: Aspose.Slides for C++ API referencia
description: A blokk gyermekelemeit a megadott karakterekkel (például zárójelekkel vagy más kereteléssel) veszi körül, és elválasztja egy szeparátor karakterrel
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) metódus

A blokk gyermekelemeket a megadott karakterekkel, például zárójelekkel vagy más kereteléssel veszi körül, és elválasztja egy szeparátor karakterrel

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char16_t | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char16_t | Záró karakter (általában jobb zárójel) |
| separatorCharacter | char16_t | Elválasztó karakter |

### Visszatérési érték

A [IMathDelimiter](../../imathdelimiter/) típusú matematikai elem, amely tartalmazza a megadott karaktereket keretként és elválasztóként
## Megjegyzések

Példa: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathDelimiter](../../imathdelimiter/)
* Osztály [IMathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)