---
title: IGeometryPath
second_title: Aspose.Slides for Java API Referencia
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
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű szegmenst a geometriai útvonalból. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Vonalat ad az útvonal végéhez |
| [lineTo(float x, float y)](#lineTo-float-float-) | Vonalat ad az útvonal végéhez |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Vonalat ad a megadott helyre az útvonalban |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Vonalat ad a megadott helyre az útvonalban |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Köbös Bezier-görbét ad az útvonal végéhez |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Köbös Bezier-görbét ad az útvonal végéhez |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Köbös Bezier-görbét ad a megadott helyre az útvonalban |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Köbös Bezier-görbét ad a megadott helyre az útvonalban |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Kvadratikus Bezier-görbét ad az útvonal végéhez |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Kvadratikus Bezier-görbét ad az útvonal végéhez |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Kvadratikus Bezier-görbét ad a megadott helyre az útvonalban |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Kvadratikus Bezier-görbét ad a megadott helyre az útvonalban |
| [closeFigure()](#closeFigure--) | Lezárja az aktuális alakzatot ezen az útvonalon |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Beállítja a következő pont helyzetét. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Beállítja a következő pont helyzetét. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Hozzáfűzi a megadott ívet az útvonalhoz. |
| [getFillMode()](#getFillMode--) | Beállítja a kitöltési módot |
| [setFillMode(byte value)](#setFillMode-byte-) | Beállítja a kitöltési módot |
| [getStroke()](#getStroke--) | Beállítja a körvonal megjelenését |
| [setStroke(boolean value)](#setStroke-boolean-) | Beállítja a körvonal megjelenését |
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

Eltávolítja a megadott indexű szegmenst a geometriai útvonalból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő geometriai útvonal indexe. |
### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

Vonalat ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | A vonal végepontja |
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
### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

Vonalat ad a megadott helyre az útvonalban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Végepont |
| index | long | A szegmens indexe a PathData-ban |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Vonalat ad a megadott helyre az útvonalban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A pont X koordinátája |
| y | float | A pont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Köbös Bezier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Első iránypont |
| point2 | java.awt.geom.Point2D.Float | Második iránypont |
| point3 | java.awt.geom.Point2D.Float | Végepont |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Köbös Bezier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az első iránypont X koordinátája |
| y1 | float | Az első iránypont Y koordinátája |
| x2 | float | A második iránypont X koordinátája |
| y2 | float | A második iránypont Y koordinátája |
| x3 | float | Az végpont X koordinátája |
| y3 | float | Az végpont Y koordinátája |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Köbös Bezier-görbét ad a megadott helyre az útvonalban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Első iránypont |
| point2 | java.awt.geom.Point2D.Float | Második iránypont |
| point3 | java.awt.geom.Point2D.Float | Végepont |
| index | long | A szegmens indexe a PathData-ban |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Köbös Bezier-görbét ad a megadott helyre az útvonalban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az első iránypont X koordinátája |
| y1 | float | Az első iránypont Y koordinátája |
| x2 | float | A második iránypont X koordinátája |
| y2 | float | A második iránypont Y koordinátája |
| x3 | float | Az végpont X koordinátája |
| y3 | float | Az végpont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Kvadratikus Bezier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Iránypont |
| point2 | java.awt.geom.Point2D.Float | Végepont |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Kvadratikus Bezier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Iránypont X koordinátája |
| y1 | float | Iránypont Y koordinátája |
| x2 | float | Végepont X koordinátája |
| y2 | float | Végepont Y koordinátája |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Kvadratikus Bezier-görbét ad a megadott helyre az útvonalban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Iránypont |
| point2 | java.awt.geom.Point2D.Float | Végepont |
| index | long | A szegmens indexe a PathData-ban |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Kvadratikus Bezier-görbét ad a megadott helyre az útvonalban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Iránypont X koordinátája |
| y1 | float | Iránypont Y koordinátája |
| x2 | float | Végepont X koordinátája |
| y2 | float | Végepont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Lezárja az aktuális alakzatot ezen az útvonalon
### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

Beállítja a következő pont helyzetét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Pont pozíciója |
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
| sweepAngle | float | Szétsöprés szög/ |
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

Beállítja a körvonal megjelenését

**Visszatér:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Beállítja a körvonal megjelenését

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |