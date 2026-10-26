---
title: CreateMathAccent()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy matematikai ékezetet, amely a megadott matematikai elemhez van alkalmazva az alapértelmezett ékezetkarakter értékkel
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metódus


Létrehoz egy matematikai ékezetet, amely a megadott matematikai elemhez van alkalmazva az alapértelmezett ékezetkarakter értékkel

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | a matematikai elem, amelyhez az ékezetet alkalmazzuk |

### Visszatérési érték

új matematikai ékezet

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metódus


Létrehoz egy matematikai ékezetet, amely a megadott matematikai elemhez van alkalmazva

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | a matematikai elem, amelyhez az ékezetet alkalmazzuk |
| accentCharacter | char16_t | ékezetkarakter |

### Visszatérési érték

új matematikai ékezet

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathAccent](../../imathaccent/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathAccentFactory](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)