---
title: MathBlock()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Inicializuje novou instanci třídy MathBlock.
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() konstruktor


Inicializuje novou instanci třídy [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Poznámky


Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) konstruktor


Vytvoří nový matematický blok a vloží do něj zadaný prvek

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Matematický prvek, který se vloží do bloku |
## Poznámky



Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) konstruktor


Vytvoří nový matematický blok a vloží do něj zadané prvky

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Matematické prvky, které se vloží do bloku |
## Poznámky



Příklad: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [MathBlock](../)
* Třída [IMathElement](../../imathelement/)
* Třída [IEnumerable](../../../system.collections.generic/ienumerable/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)