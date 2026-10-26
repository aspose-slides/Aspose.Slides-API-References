---
title: MathPhantom()
second_title: Aspose.Slides pro C++ API Reference
description: Inicializuje novou instanci třídy MathPhantom pomocí zadaného základního matematického prvku.
type: docs
weight: 144
url: /cs/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) konstruktor


Inicializuje novou instanci třídy [MathPhantom](../) pomocí zadaného základního matematického prvku.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní [IMathElement](../../imathelement/), jehož viditelnost a rozložení budou řízeny phantomem. Tento prvek definuje obsah, který může být skrytý nebo zobrazený, a přesto ovlivňuje geometrické zarovnání okolní matematiky. |
## Poznámky



Prvek phantom se používá k rezervaci nebo potlačení vizuálního prostoru svého základního výrazu, aniž by jej nutně zobrazoval. Odpovídá elementu OMML **<m:phant>**. 

Příklad: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathPhantom](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)