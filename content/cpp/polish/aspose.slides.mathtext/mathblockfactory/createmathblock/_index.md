---
title: CreateMathBlock()
second_title: Aspose.Slides dla odwołania API w C++
description: Utwórz blok matematyczny
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() metoda

Utwórz blok matematyczny

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### Wartość zwracana

nowy blok matematyczny

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metoda

Utwórz blok matematyczny i umieść w nim element

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny |

### Wartość zwracana

nowy blok matematyczny

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metoda

Utwórz blok matematyczny i umieść w nim elementy

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elementy matematyczne |

### Wartość zwracana

nowy blok matematyczny

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [MathBlockFactory](../)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathElementCollection](../../imathelementcollection/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)