---
title: Delimit()
second_title: Aspose.Slides C++ API-referenciához
description: Az összes gyermekelemet elválasztó karakterrel határolja (a szögletes zárójelek nélkül)
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) metódus

Határolja el az összes gyermekelemet a elválasztó karakterrel (a szögletes zárójelek nélkül)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char16_t | Az elválasztóként használt karakter |

### Visszatérési érték

[IMathDelimiter](../../imathdelimiter/) elem példánya

## Megjegyzések



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathDelimiter](../../imathdelimiter/)
* Osztály [IMathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)