---
title: MathBlock()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de MathBlock-klasse.
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() constructor

Initialiseert een nieuw exemplaar van de klasse [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Opmerkingen

Voorbeeld:
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) constructor

Creëert een nieuw wiskundig blok en plaatst het opgegeven element erin

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het wiskundige element om in het blok te plaatsen |
## Opmerkingen

Voorbeeld:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) constructor

Creëert een nieuw wiskundig blok en plaatst de opgegeven elementen erin

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Wiskundige elementen om in het blok te plaatsen |
## Opmerkingen

Voorbeeld:
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [MathBlock](../)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)