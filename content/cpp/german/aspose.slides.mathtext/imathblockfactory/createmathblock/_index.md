---
title: CreateMathBlock()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt einen Math-Block
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() Methode


Erstellt einen Math-Block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```


### Rückgabewert

neuer Math-Block

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) Methode


Erstellt einen Math-Block und fügt das Element darin ein

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ein Math-Element |

### Rückgabewert

neuer Math-Block

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) Methode


Erstellt einen Math-Block und fügt die Elemente darin ein

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | Math-Elemente |

### Rückgabewert

neuer Math-Block

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockFactory](../)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathElementCollection](../../imathelementcollection/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)