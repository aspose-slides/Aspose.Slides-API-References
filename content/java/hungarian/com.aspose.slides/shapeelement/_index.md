---
title: ShapeElement
second_title: Aspose.Slides Java API hivatkozás
description: Egy alakzat egy részét képviseli, amelynek ugyanaz a körvonala és kitöltési tulajdonsága.
type: docs
url: /hu/com.aspose.slides/shapeelement/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

A forma egy részét képviseli, amelynek ugyanaz a körvonala és kitöltési tulajdonsága.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParentShape()](#getParentShape--) | Visszaad egy Shape_PPT objektumot, amelyhez az elem létre lett hozva. |
| [getPathPoints()](#getPathPoints--) | Visszaad egy pontokból álló tömböt, amely meghatározza az elem útvonalának geometriáját. |
| [getPathTypes()](#getPathTypes--) | Visszaad egy byte értékekből álló tömböt, amely megadja az elem útvonalában lévő minden pont típusát. |
| [getFillSource()](#getFillSource--) | Visszaad információt arról, hogyan kell kitölteni egy elemet. |
| [getStrokeSource()](#getStrokeSource--) | Visszaad információt arról, hogyan kell körvonalazni egy elemet. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Visszaad egy Shape_PPT objektumot, amelyhez az elem létre lett hozva. Csak olvasható [Shape](../../com.aspose.slides/shape).

**Visszatérési érték:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

Visszaad egy pontokból álló tömböt, amely meghatározza az elem útvonalának geometriáját.

**Visszatérési érték:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Visszaad egy byte értékekből álló tömböt, amely megadja az elem útvonalában lévő minden pont típusát.

**0** A pont egy ábra elejét jelzi.

**1** A pont egy vonal két végpontja közül az egyiket jelzi.

**3** A pont egy végpont vagy irányító pont egy köbös Bézier-görbében.

**7** Kitakarja az összes bitet, kivéve a három legalsó bitet, amelyek a pont típusát jelzik.

**16** A megfelelő szegmens szakaszos.

**32** A pont egy marker.

**128** A pont egy zárt alútvonal (ábra) utolsó pontja.

**129** Egy adatpont, amely egyszerre vonal szegmens végpontja és egy zárt alútvonal utolsó pontja.

**Visszatérési érték:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Visszaad információt arról, hogyan kell kitölteni egy elemet. Csak olvasható [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Visszatérési érték:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Visszaad információt arról, hogyan kell körvonalazni egy elemet. Csak olvasható [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Visszatérési érték:**
byte