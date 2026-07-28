---
title: CreateMathBlock()
second_title: Aspose.Slides C++ API-referencia
description: Matematikai blokk létrehozása
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() metódus

Matematikai blokk létrehozása

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Visszatérési érték

új matematikai blokk

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metódus

Matematikai blokk létrehozása, és az elem elhelyezése benne

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Egy matematikai elem |

### Visszatérési érték

új matematikai blokk

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metódus

Matematikai blokk létrehozása, és elemek elhelyezése benne

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | matematikai elemek |

### Visszatérési érték

új matematikai blokk

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathBlockFactory](../)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathElementCollection](../../imathelementcollection/)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)