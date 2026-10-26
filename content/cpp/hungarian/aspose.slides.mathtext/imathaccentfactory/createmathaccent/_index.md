---
title: CreateMathAccent()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy matematikai akcentust, amelyet egy megadott matematikai elemhez alkalmaz a alapértelmezett akcentus karakter értékkel
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metódus

Létrehoz egy matematikai akcentust a megadott matematikai elemhez, az alapértelmezett akcentus karakter értékkel

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikai elem, amelyhez az akcentust alkalmazzuk |

### Visszatérési érték

új matematikai akcentus

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metódus

Létrehoz egy matematikai akcentust a megadott matematikai elemhez

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikai elem, amelyhez az akcentust alkalmazzuk |
| accentCharacter | char16_t | akcentus karakter |

### Visszatérési érték

új matematikai akcentus

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathAccent](../../imathaccent/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathAccentFactory](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)