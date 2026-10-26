---
title: CreateMathAccent()
second_title: Aspose.Slides pro C++ API referenci
description: Vytvoří matematický akcent, který se použije na zadaný matematický prvek s výchozí hodnotou akcentovacího znaku
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metoda


Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou akcentovacího znaku

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje akcent |

### Návratová hodnota

nový matematický akcent

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metoda


Vytvoří matematický akcent aplikovaný na zadaný matematický prvek

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje akcent |
| accentCharacter | char16_t | akcentní znak |

### Návratová hodnota

nový matematický akcent

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathAccent](../../imathaccent/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathAccentFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)