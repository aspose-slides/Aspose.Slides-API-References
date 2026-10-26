---
title: SmartArtShape
second_title: Aspose.Slides Android számára a Java API hivatkozáson keresztül
description: A SmartArt alakzatot képviseli
type: docs
url: /hu/com.aspose.slides/smartartshape/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Az összes megvalósított interfész:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

A SmartArt alakzatot képviseli
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShapeType()](#getShapeType--) | Visszaadja vagy beállítja a geometria előre beállított típusát. |
| [setShapeType(int value)](#setShapeType-int-) | Visszaadja vagy beállítja a geometria előre beállított típusát. |
| [getTextFrame()](#getTextFrame--) | Visszaadja a SmartArt alakzat szövegét. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Visszaadja vagy beállítja a geometria előre beállított típusát. Megjegyzés: az érték változtatásakor az összes módosítási érték visszaáll az alapértelmezett értékére. Olvasás/írás [ShapeType](../../com.aspose.slides/shapetype).

**Visszatérési érték:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Visszaadja vagy beállítja a geometria előre beállított típusát. Megjegyzés: az érték változtatásakor az összes módosítási érték visszaáll az alapértelmezett értékére. Olvasás/írás [ShapeType](../../com.aspose.slides/shapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Visszaadja a SmartArt alakzat szövegét. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)