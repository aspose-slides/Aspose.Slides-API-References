---
title: CreateMathBlock()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen mathematischen Block
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() Methode

Erstellt einen mathematischen Block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### Rückgabewert

neuer mathematischer Block

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) Methode

Erstellt einen mathematischen Block und platziert das Element darin

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ein mathematisches Element |

### Rückgabewert

neuer mathematischer Block

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) Methode

Erstellt einen mathematischen Block und platziert die Elemente darin

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | Mathematische Elemente |

### Rückgabewert

neuer mathematischer Block

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [MathBlockFactory](../)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathElementCollection](../../imathelementcollection/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)