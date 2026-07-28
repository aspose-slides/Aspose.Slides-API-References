---
title: CreateMathBlock()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Utwórz blok matematyczny
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() metoda


Utwórz blok matematyczny

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```


### Wartość zwracana

nowy blok matematyczny

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metoda


Utwórz blok matematyczny i umieść w nim element

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element matematyczny |

### Wartość zwracana

nowy blok matematyczny

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metoda


Utwórz blok matematyczny i umieść w nim elementy

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
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
* Klasa [IMathBlockFactory](../)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathElementCollection](../../imathelementcollection/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)