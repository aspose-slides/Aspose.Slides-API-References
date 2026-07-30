---
title: CreateMathBlock()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvořte matematický blok
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() metoda

Vytvořte matematický blok

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### Návratová hodnota

nový matematický blok

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metoda

Vytvořte matematický blok a umístěte do něj matematický prvek

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Matematický prvek |

### Návratová hodnota

nový matematický blok

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metoda

Vytvořte matematický blok a umístěte do něj matematické prvky

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | matematické prvky |

### Návratová hodnota

nový matematický blok

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathBlock](../../imathblock/)
* třída [MathBlockFactory](../)
* třída [IMathElement](../../imathelement/)
* třída [IMathElementCollection](../../imathelementcollection/)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)