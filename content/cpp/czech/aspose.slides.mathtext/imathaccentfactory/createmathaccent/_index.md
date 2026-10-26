---
title: CreateMathAccent()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou akcentovacího znaku
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metoda

Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou akcentovacího znaku

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje akcent |

### Návratová hodnota

nový matematický akcent

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metoda

Vytvoří matematický akcent aplikovaný na zadaný matematický prvek

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje akcent |
| accentCharacter | char16_t | akcentovací znak |

### Návratová hodnota

nový matematický akcent

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathAccent](../../imathaccent/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathAccentFactory](../)
* Obor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)