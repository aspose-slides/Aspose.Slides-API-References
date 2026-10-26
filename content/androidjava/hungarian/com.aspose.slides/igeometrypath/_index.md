---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: A GeometryShape geometriai útvonalát reprezentálja
type: docs
url: /hu/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

A GeometryShape geometriai útvonalát reprezentálja
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPathData()](#getPathData--) | Visszaadja a GeometryShape geometriai útvonalát útvonal-szegmensek tömbjeként. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a geometriai útvonal adott indexű szegmensét. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Vonalat ad az útvonal végéhez |
| [lineTo(float x, float y)](#lineTo-float-float-) | Vonalat ad az útvonal végéhez |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Vonalat ad az útvonal megadott helyére |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Vonalat ad az útvonal megadott helyére |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Köbös Bézier-görbét ad az útvonal végéhez |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Köbös Bézier-görbét ad az útvonal végéhez |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Köbös Bézier-görbét ad az útvonal megadott helyére |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Köbös Bézier-görbét ad az útvonal megadott helyére |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Kvadratikus Bézier-görbét ad az útvonal végéhez |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Kvadratikus Bézier-görbét ad az útvonal végéhez |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Kvadratikus Bézier-görbét ad az útvonal megadott helyére |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Kvadratikus Bézier-görbét ad az útvonal megadott helyére |
| [closeFigure()](#closeFigure--) | Lezárja a jelenlegi alakzatot ezen az útvonalon |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Beállítja a következő pont helyzetét. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Beállítja a következő pont helyzetét. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Hozzáfűzi a megadott ívet az útvonalhoz. |
| [getFillMode()](#getFillMode--) | Beállítja a kitöltési módot |
| [setFillMode(byte value)](#setFillMode-byte-) | Beállítja a kitöltési módot |
| [getStroke()](#getStroke--) | Beállítja a vonal (stroke) megjelenését |
| [setStroke(boolean value)](#setStroke-boolean-) | Beállítja a vonal (stroke) megjelenését |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

Visszaadja a GeometryShape geometriai útvonalát útvonal-szegmensek tömbjeként.

**Visszatér:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a geometriai útvonal adott indexű szegmensét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A geometriai útvonal indexe, amelyet törölni kell. |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

Vonalat ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | android.graphics.PointF | A vonal végpontja |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Vonalat ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A vonal végpontjának X koordinátája |
| y | float | A vonal végpontjának Y koordinátája |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

Vonalat ad az útvonal megadott helyére

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | android.graphics.PointF | Végpont |
| index | long | A szegmens indexe a PathData-ban |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Vonalat ad az útvonal megadott helyére

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A pont X koordinátája |
| y | float | A pont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Köbös Bézier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | android.graphics.PointF | Az első iránypont |
| point2 | android.graphics.PointF | A második iránypont |
| point3 | android.graphics.PointF | Végpont |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Köbös Bézier-görbét ad az útvonal végéhez

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
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Köbös Bézier-görbét ad az útvonal megadott helyére

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | android.graphics.PointF | Az első iránypont |
| point2 | android.graphics.PointF | A második iránypont |
| point3 | android.graphics.PointF | Végpont |
| index | long | A szegmens indexe a PathData-ban |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Köbös Bézier-görbét ad az útvonal megadott helyére

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az első iránypont X koordinátája |
| y1 | float | Az első iránypont Y koordinátája |
| x2 | float | A második iránypont X koordinátája |
| y2 | float | A második iránypont Y koordinátája |
| x3 | float | A végpont X koordinátája |
| y3 | float | A végpont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

Kvadratikus Bézier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | android.graphics.PointF | Iránypont |
| point2 | android.graphics.PointF | Végpont |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Kvadratikus Bézier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az iránypont X koordinátája |
| y1 | float | Az iránypont Y koordinátája |
| x2 | float | A végpont X koordinátája |
| y2 | float | A végpont Y koordinátája |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Kvadratikus Bézier-görbét ad az útvonal megadott helyére

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | android.graphics.PointF | Iránypont |
| point2 | android.graphics.PointF | Végpont |
| index | long | A szegmens indexe a PathData-ban |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Kvadratikus Bézier-görbét ad az útvonal megadott helyére

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az iránypont X koordinátája |
| y1 | float | Az iránypont Y koordinátája |
| x2 | float | A végpont X koordinátája |
| y2 | float | A végpont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Lezárja a jelenlegi alakzatot ezen az útvonalon
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

Beállítja a következő pont helyzetét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | android.graphics.PointF | Pont pozíciója |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Beállítja a következő pont helyzetét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A pont X koordinátája |
| y | float | A pont Y koordinátája |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Hozzáfűzi a megadott ívet az útvonalhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | float | A téglalap szélessége |
| heigth | float | A téglalap magassága |
| startAngle | float | Kezdő szög. |
| sweepAngle | float | Átmeneti szög/ |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

Beállítja a kitöltési módot

**Visszatér:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

Beállítja a kitöltési módot

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

Beállítja a vonal (stroke) megjelenését

**Visszatér:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Beállítja a vonal (stroke) megjelenését

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |