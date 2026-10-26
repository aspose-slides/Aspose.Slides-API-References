---
title: ShapeElement
second_title: Aspose.Slides for Android Java API hivatkozás
description: Egy alakzat olyan részét képviseli, amelynek körvonala és kitöltési tulajdonságai azonosak.
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

Egy alakzat olyan részét képviseli, amelynek körvonala és kitöltési tulajdonságai azonosak.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParentShape()](#getParentShape--) | Visszaad egy Shape_PPT objektumot, amelyhez az elem létrehozva lett. |
| [getPathPoints()](#getPathPoints--) | Visszaad egy ponttömböt, amely meghatározza az elem útvonalának geometriáját. |
| [getPathTypes()](#getPathTypes--) | Visszaad egy bájtértékek tömbjét, amely meghatározza az egyes pontok típusát az elem útvonalában. |
| [getFillSource()](#getFillSource--) | Visszaad információt arról, hogyan kell kitölteni egy elemet. |
| [getStrokeSource()](#getStrokeSource--) | Visszaad információt arról, hogyan kell körvonalazni egy elemet. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Visszaad egy Shape_PPT objektumot, amelyhez az elem létrehozva lett. Csak olvasható [Shape](../../com.aspose.slides/shape).

**Visszatér:**  
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Visszaad egy ponttömböt, amely meghatározza az elem útvonalának geometriáját.

**Visszatér:**  
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Visszaad egy bájtértékek tömbjét, amely meghatározza az egyes pontok típusát az elem útvonalában.

**0** Jelzi, hogy a pont egy ábra kezdete.

**1** Jelzi, hogy a pont egy vonal két végpontja közül az egyik.

**3** Jelzi, hogy a pont egy végpont vagy vezérlőpont egy köbös Bézier görbében.

**7** Maszk minden bitet, kivéve a három legalacsonyabb sorrendi bitet, amelyek a pont típusát jelzik.

**16** Meghatározza, hogy a megfelelő szegmens szaggatott.

**32** Meghatározza, hogy a pont egy jelző.

**128** Meghatározza, hogy a pont a zárt alútvonal (ábra) utolsó pontja.

**129** Jelzi, hogy egy adatpont egyszerre vonalszakasz végpont és a zárt alútvonal utolsó pontja.

**Visszatér:**  
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Visszaad információt arról, hogyan kell kitölteni egy elemet. Csak olvasható [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Visszatér:**  
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Visszaad információt arról, hogyan kell körvonalazni egy elemet. Csak olvasható [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Visszatér:**  
byte