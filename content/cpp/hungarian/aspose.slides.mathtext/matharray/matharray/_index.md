---
title: MathArray()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy matematikai tömböt, és elhelyezi benne a megadott elemet
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) konstruktor


Létrehoz egy matematikai tömböt, és elhelyezi benne a megadott elemet

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az elem, amelyet a tömbbe kell helyezni |
## Megjegyzések



Példa: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) konstruktor


Létrehoz egy matematikai tömböt, és elhelyezi benne a megadott elemeket

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Az elemek, amelyeket a tömbbe kell helyezni |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathArray](../)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)