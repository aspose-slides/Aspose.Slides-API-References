---
title: CreateMathBlock()
second_title: Aspose.Slides för C++ API-referens
description: Skapa ett matematiskt block
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() metod

Skapa ett matematiskt block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Returvärde

nytt matematiskt block

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metod

Skapa ett matematiskt block och placera elementet i det

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ett matematikelement |

### Returvärde

nytt matematiskt block

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metod

Skapa ett matematiskt block och placera elementen i det

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | Matematikelement |

### Returvärde

nytt matematiskt block

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [IMathBlockFactory](../)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathElementCollection](../../imathelementcollection/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)