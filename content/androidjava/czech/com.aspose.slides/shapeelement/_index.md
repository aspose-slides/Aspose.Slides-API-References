---
title: ShapeElement
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Představuje část tvaru se stejnými vlastnostmi obrysu a výplně.
type: docs
url: /cs/com.aspose.slides/shapeelement/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Představuje část tvaru se stejnými vlastnostmi obrysu a výplně.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParentShape()](#getParentShape--) | Vrací Shape_PPT, pro který byl vytvořen prvek. |
| [getPathPoints()](#getPathPoints--) | Vrací pole bodů, které definují geometrii cesty prvku. |
| [getPathTypes()](#getPathTypes--) | Vrací pole bajtových hodnot, které určují typ každého bodu v cestě prvku. |
| [getFillSource()](#getFillSource--) | Vrací informace o tom, jak vyplnit prvek. |
| [getStrokeSource()](#getStrokeSource--) | Vrací informace o tom, jak obkreslit prvek. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Vrací Shape_PPT, pro který byl vytvořen prvek. Pouze pro čtení [Shape](../../com.aspose.slides/shape).

**Vrací:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Vrací pole bodů, které definují geometrii cesty prvku.

**Vrací:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Vrací pole bajtových hodnot, které určují typ každého bodu v cestě prvku.

**0** Indikuje, že bod je začátkem figury.

**1** Indikuje, že bod je jedním ze dvou koncových bodů čáry.

**3** Indikuje, že bod je koncový nebo řídící bod kubické Bezierovy křivky.

**7** Maskuje všechny bity kromě tří nízkých bitů, které určují typ bodu.

**16** Určuje, že odpovídající úsek je čárkovaný.

**32** Určuje, že bod je značkou.

**128** Určuje, že bod je posledním bodem uzavřené podcesty (figury).

**129** Indikuje datový bod, který je zároveň koncovým bodem úseku a posledním bodem uzavřené podcesty.

**Vrací:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Vrací informace o tom, jak vyplnit prvek. Pouze pro čtení [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Vrací:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Vrací informace o tom, jak obkreslit prvek. Pouze pro čtení [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Vrací:**
byte