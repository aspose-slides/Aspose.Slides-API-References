---
title: MathBlock()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Inicjalizuje nową instancję klasy MathBlock.
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() konstruktor

Inicjalizuje nową instancję klasy [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Uwagi

Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) konstruktor

Tworzy nowy blok matematyczny i umieszcza w nim określony element.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element matematyczny do umieszczenia w bloku |
## Uwagi

Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) konstruktor

Tworzy nowy blok matematyczny i umieszcza w nim określone elementy.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Elementy matematyczne do umieszczenia w bloku |
## Uwagi

Przykład: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Zobacz również

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [MathBlock](../)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)