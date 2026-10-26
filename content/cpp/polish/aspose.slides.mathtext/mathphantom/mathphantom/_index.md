---
title: MathPhantom()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Inicjalizuje nową instancję klasy MathPhantom przy użyciu określonego elementu bazowego matematycznego.
type: docs
weight: 144
url: /pl/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) konstruktor


Inicjalizuje nową instancję klasy [MathPhantom](../) przy użyciu określonego elementu bazowego matematycznego.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bazowy [IMathElement](../../imathelement/), którego widoczność i układ będą kontrolowane przez fantom. Ten element definiuje treść, która może być ukryta lub pokazana, jednocześnie wpływając na geometryczne wyrównanie otaczającej matematyki. |
## Uwagi



Element fantom jest używany do zarezerwowania lub zablokowania wizualnej przestrzeni swojej wyrażenia bazowego bez konieczności jego wyświetlania. Odpowiada elementowi OMML **<m:phant>**. 

Przykład: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathPhantom](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)