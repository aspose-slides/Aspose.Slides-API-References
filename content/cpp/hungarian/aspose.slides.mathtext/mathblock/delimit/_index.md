---
title: Delimit()
second_title: Aspose.Slides C++ API referencia
description: Elválasztja a gyermekelemeket a szeparátor karakterrel (zárójelek nélkül)
type: docs
weight: 209
url: /hu/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) metódus


Elválasztja a gyermekelemeket a szeparátor karakterrel (zárójelek nélkül)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char16_t | Szeparátor karakter |

### Visszatérési érték

A(z) [IMathDelimiter](../../imathdelimiter/) típusú matematikai elem
## Megjegyzések



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathDelimiter](../../imathdelimiter/)
* Osztály [MathBlock](../)
* Névterület [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)