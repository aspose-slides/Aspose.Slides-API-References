---
title: get_PathTypes()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací pole bajtových hodnot, které určují typ každého bodu v cestě prvku.
type: docs
weight: 27
url: /cs/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() metoda

Vrací pole bajtových hodnot, které určují typ každého bodu v cestě prvku.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Poznámky

**0** Udává, že bod je začátkem figury.

**1** Udává, že bod je jedním ze dvou koncových bodů čáry.

**3** Udává, že bod je koncovým bodem nebo řídícím bodem kubického Bézierova spline.

**7** Maskuje všechny bity kromě tří nízkých bitů, které určují typ bodu.

**16** Určuje, že odpovídající segment je čárkovaný.

**32** Určuje, že bod je značkou.

**128** Určuje, že bod je posledním bodem uzavřené podcesty (figury).

**129** Udává datový bod, který je současně koncovým bodem úsečky a posledním bodem uzavřené podcesty.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ShapeElement](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)