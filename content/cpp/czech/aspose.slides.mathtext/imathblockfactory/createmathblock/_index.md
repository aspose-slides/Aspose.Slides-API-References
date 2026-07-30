---
title: CreateMathBlock()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří matematický blok
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() metoda

Vytvoří matematický blok

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Návratová hodnota

nový matematický blok

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metoda

Vytvoří matematický blok a umístí do něj prvek

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Matematický prvek |

### Návratová hodnota

nový matematický blok

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metoda

Vytvoří matematický blok a umístí do něj prvky

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | matematické prvky |

### Návratová hodnota

nový matematický blok

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathBlockFactory](../)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathElementCollection](../../imathelementcollection/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)