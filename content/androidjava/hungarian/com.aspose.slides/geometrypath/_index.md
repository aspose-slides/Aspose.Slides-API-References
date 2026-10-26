---
title: GeometryPath
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A GeometryShape geometriai útvonalát reprezentálja
type: docs
url: /hu/com.aspose.slides/geometrypath/
---
**Öröklés:**  
java.lang.Object

**Minden megvalósított interfész:**  
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)  
```
public final class GeometryPath implements IGeometryPath
```

A GeometryShape geometriai útvonalát reprezentálja
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Létrehozza a GeometryPath példányát |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPathData()](#getPathData--) | Visszaadja a GeometryShape geometriai útvonalát útvonal szegmensek tömbjeként. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a szegmenst a geometriai útvonal adott indexén. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Vonalat ad az útvonal végéhez |
| [lineTo(float x, float y)](#lineTo-float-float-) | Vonalat ad az útvonal végéhez |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Vonalat ad a útvonal megadott helyére |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Vonalat ad a útvonal megadott helyére |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Hozzáad egy köbös Bézier görbét az útvonal végéhez |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Hozzáad egy köbös Bézier görbét az útvonal végéhez |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Hozzáad egy köbös Bézier görbét a útvonal megadott helyére |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Hozzáad egy köbös Bézier görbét a útvonal megadott helyére |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Hozzáad egy kvadratikus Bézier görbét az útvonal végéhez |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Hozzáad egy kvadratikus Bézier görbét az útvonal végéhez |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Hozzáad egy kvadratikus Bézier görbét a útvonal megadott helyére |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Hozzáad egy kvadratikus Bézier görbét a útvonal megadott helyére |
| [closeFigure()](#closeFigure--) | Bezárja a jelenlegi alakzatot az útvonalban |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Beállítja a következő pont pozícióját. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Beállítja a következő pont pozícióját. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Hozzáfűzi a megadott ívet az útvonalhoz. |
| [getFillMode()](#getFillMode--) | Beállítja a kitöltési módot |
| [setFillMode(byte value)](#setFillMode-byte-) | Beállítja a kitöltési módot |
| [getStroke()](#getStroke--) | Beállítja a körvonal megjelenését |
| [setStroke(boolean value)](#setStroke-boolean-) | Beállítja a körvonal megjelenését |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Létrehozza a GeometryPath példányát

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Visszaadja a GeometryShape geometriai útvonalát útvonal szegmensek tömbjeként.

**Visszatérési érték:**  
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a szegmenst a geometriai útvonal adott indexén.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő geometriai útvonal indexe. |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Vonalat ad az útvonal végéhez

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | android.graphics.PointF | A vonal végpontja |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Vonalat ad az útvonal végéhez

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A vonal végpontjának X koordinátája |
| y | float | A vonal végpontjának Y koordinátája |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Vonalat ad a útvonal megadott helyére

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | android.graphics.PointF | Végpont |
| index | long | A szegmens indexe a PathData-ben |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Vonalat ad a útvonal megadott helyére

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A pont X koordinátája |
| y | float | A pont Y koordinátája |
| index | long | A szegmens indexe a PathData-ben |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Hozzáad egy köbös Bézier görbét az útvonal végéhez

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | android.graphics.PointF | Első iránypont |
| point2 | android.graphics.PointF | Második iránypont |
| point3 | android.graphics.PointF | Végpont |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Hozzáad egy köbös Bézier görbét az útvonal végéhez

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az első iránypont X koordinátája |
| y1 | float | Az első iránypont Y koordinátája |
| x2 | float | A második iránypont X koordinátája |
| y2 | float | A második iránypont Y koordinátája |
| x3 | float | A végpont X koordinátája |
| y3 | float | A végpont Y koordinátája |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Hozzáad egy köbös Bézier görbét a megadott helyre az útvonalban

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | android.graphics.PointF | Első iránypont |
| point2 | android.graphics.PointF | Második iránypont |
| point3 | android.graphics.PointF | Végpont |
| index | long | A szegmens indexe a PathData-ben |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Hozzáad egy köbös Bézier görbét a megadott helyre az útvonalban

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az első iránypont X koordinátája |
| y1 | float | Az első iránypont Y koordinátája |
| x2 | float | A második iránypont X koordinátája |
| y2 | float | A második iránypont Y koordinátája |
| x3 | float | A végpont X koordinátája |
| y3 | float | A végpont Y koordinátája |
| index | long | A szegmens indexe a PathData-ben |
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Hozzáad egy kvadratikus Bézier görbét az útvonal végéhez

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | android.graphics.PointF | Iránypont |
| point2 | android.graphics.PointF | Végpont |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Hozzáad egy kvadratikus Bézier görbét az útvonal végéhez

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az iránypont X koordinátája |
| y1 | float | Az iránypont Y koordinátája |
| x2 | float | A végpont X koordinátája |
| y2 | float | A végpont Y koordinátája |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Hozzáad egy kvadratikus Bézier görbét a megadott helyre az útvonalban

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | android.graphics.PointF | Iránypont |
| point2 | android.graphics.PointF | Végpont |
| index | long | A szegmens indexe a PathData-ben |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Hozzáad egy kvadratikus Bézier görbét a megadott helyre az útvonalban

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az iránypont X koordinátája |
| y1 | float | Az iránypont Y koordinátája |
| x2 | float | A végpont X koordinátája |
| y2 | float | A végpont Y koordinátája |
| index | long | A szegmens indexe a PathData-ben |
### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Bezárja a jelenlegi alakzatot az útvonalban
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Beállítja a következő pont pozícióját.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | android.graphics.PointF | Pont pozíció |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Beállítja a következő pont pozícióját.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A pont X koordinátája |
| y | float | A pont Y koordinátája |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Hozzáfűzi a megadott ívet az útvonalhoz.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | float | A téglalap szélessége |
| heigth | float | A téglalap magassága |
| startAngle | float | Kezdő szög. |
| sweepAngle | float | Sweep angle/ |
### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Beállítja a kitöltési módot

**Visszatérési érték:**  
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Beállítja a kitöltési módot

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Beállítja a körvonal megjelenését

**Visszatérési érték:**  
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Beállítja a körvonal megjelenését

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |