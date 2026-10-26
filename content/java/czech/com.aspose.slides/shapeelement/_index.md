---
title: ShapeElement
second_title: Aspose.Slides pro Java API Reference
description: Zastupuje část tvaru se stejnými vlastnostmi obrysu a výplně.
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

Zastupuje část tvaru se stejnými vlastnostmi obrysu a výplně.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParentShape()](#getParentShape--) | Vrací Shape_PPT, pro který byl prvek vytvořen. |
| [getPathPoints()](#getPathPoints--) | Získá pole bodů definujících geometrii cesty prvku. |
| [getPathTypes()](#getPathTypes--) | Získá pole hodnot typu byte, které určují typ každého bodu v cestě prvku. |
| [getFillSource()](#getFillSource--) | Vrací informace o tom, jak vyplnit prvek. |
| [getStrokeSource()](#getStrokeSource--) | Vrací informace o tom, jak obrysnout prvek. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Vrací Shape_PPT, pro který byl prvek vytvořen. Pouze pro čtení [Shape](../../com.aspose.slides/shape).

**Vrací:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


Získá pole bodů definujících geometrii cesty prvku.

**Vrací:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


Získá pole hodnot typu byte, které určují typ každého bodu v cestě prvku.

**0** Označuje, že bod je začátkem figure.

**1** Označuje, že bod je jedním ze dvou koncových bodů úsečky.

**3** Označuje, že bod je koncový nebo řídící bod kubické Bezierovy křivky.

**7** Maskuje všechny bity kromě tří nejnižších, které určují typ bodu.

**16** Určuje, že odpovídající segment je čárkovaný.

**32** Určuje, že bod je značka.

**128** Určuje, že bod je poslední bod uzavřené podcesty (figure).

**129** Označuje datový bod, který je zároveň koncovým bodem úsečkového segmentu a posledním bodem uzavřené podcesty.

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


Vrací informace o tom, jak obrysnout prvek. Pouze pro čtení [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Vrací:**
byte