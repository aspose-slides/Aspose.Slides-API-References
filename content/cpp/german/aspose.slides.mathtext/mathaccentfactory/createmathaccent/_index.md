---
title: CreateMathAccent()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element mit dem Standard-Akzentzeichenwert angewendet wird
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) Methode

Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element mit dem Standard-Akzentzeichenwert angewendet wird

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | mathematisches Element, auf das der Akzent angewendet wird |

### Rückgabewert

neuer mathematischer Akzent

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) Methode

Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | mathematisches Element, auf das der Akzent angewendet wird |
| accentCharacter | char16_t | Akzentzeichen |

### Rückgabewert

neuer mathematischer Akzent

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathAccent](../../imathaccent/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathAccentFactory](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)