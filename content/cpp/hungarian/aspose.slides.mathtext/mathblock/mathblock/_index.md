---
title: MathBlock()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza a MathBlock osztály egy új példányát.
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() konstruktor


Létrehozza a(z) [MathBlock](../) osztály egy új példányát.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Megjegyzések


Példa: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) konstruktor


Létrehoz egy új matematikai blokkot, és az adott elemet belehelyezi

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A blokkba elhelyezendő matematikai elem |
## Megjegyzések



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) konstruktor


Létrehoz egy új matematikai blokkot, és a megadott elemeket belehelyezi

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | A blokkba elhelyezendő matematikai elemek |
## Megjegyzések



Példa: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [MathBlock](../)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)