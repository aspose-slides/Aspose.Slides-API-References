---
title: MathArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein mathematisches Array und legt das angegebene Element darin ab
type: docs
weight: 144
url: /de/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) Konstruktor


Erstellt ein mathematisches Array und legt das angegebene Element darin ab

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Element, das im Array platziert werden soll |
## Hinweise



Beispiel: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) Konstruktor


Erstellt ein mathematisches Array und legt die angegebenen Elemente darin ab

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Die Elemente, die im Array platziert werden sollen |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathArray](../)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)