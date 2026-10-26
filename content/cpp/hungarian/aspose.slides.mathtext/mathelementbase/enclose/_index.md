---
title: Enclose()
second_title: Aspose.Slides C++ API referencia
description: Matematikai elemet zárójelek közé helyez
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() metódus


Zárójelek közé helyezi a matematikai elemet

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Visszatérési érték

A [IMathDelimiter](../../imathdelimiter/) típusú matematikai elem, amely tartalmazza a zárójelet
## Megjegyzés



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) metódus


Megadott karakterek közé helyezi a matematikai elemet, például zárójelek vagy más karakterek keretezéseként

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char16_t | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char16_t | Záró karakter (általában jobb zárójel) |

### Visszatérési érték

A [IMathDelimiter](../../imathdelimiter/) típusú matematikai elem, amely a megadott karaktereket keretezésként tartalmazza
## Megjegyzés



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathDelimiter](../../imathdelimiter/)
* Osztály [MathElementBase](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)