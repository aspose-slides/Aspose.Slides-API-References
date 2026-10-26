---
title: SmartArtShape
second_title: Aspose.Slides Java API Referencia
description: A SmartArt alakzatot képviseli
type: docs
url: /hu/com.aspose.slides/smartartshape/
---
**Öröklés:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Minden megvalósított interfész:**  
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)  
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

A SmartArt alakzatot képviseli

## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getShapeType()](#getShapeType--) | Visszaadja vagy beállítja a geometria előre definiált típusát. |
| [setShapeType(int value)](#setShapeType-int-) | Visszaadja vagy beállítja a geometria előre definiált típusát. |
| [getTextFrame()](#getTextFrame--) | Visszaadja a SmartArt alakzat szövegét. |

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Visszaadja vagy beállítja a geometria előre definiált típusát. Megjegyzés: az érték módosításakor az összes igazítási érték visszaáll az alapértelmezett értékekre. Olvasás/írás [ShapeType](../../com.aspose.slides/shapetype).

**Visszatérési érték:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Visszaadja vagy beállítja a geometria előre definiált típusát. Megjegyzés: az érték módosításakor az összes igazítási érték visszaáll az alapértelmezett értékekre. Olvasás/írás [ShapeType](../../com.aspose.slides/shapetype).

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