---
title: CreateMathAccent()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element mit dem Standard-Akzentzeichenwert angewendet wird
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) Methode

Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element mit dem Standard-Akzentzeichenwert angewendet wird.

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathematisches Element, auf das der Akzent angewendet wird |

### Rückgabewert

neuer mathematischer Akzent

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) Methode

Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird.

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathematisches Element, auf das der Akzent angewendet wird |
| accentCharacter | char16_t | Akzentzeichen |

### Rückgabewert

neuer mathematischer Akzent

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathAccent](../../imathaccent/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathAccentFactory](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)