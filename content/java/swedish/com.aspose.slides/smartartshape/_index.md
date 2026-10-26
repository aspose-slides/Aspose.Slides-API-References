---
title: SmartArtShape
second_title: Aspose.Slides för Java API-referens
description: Representerar SmartArt shape
type: docs
url: /sv/com.aspose.slides/smartartshape/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Representerar SmartArt shape
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapeType()](#getShapeType--) | Returnerar eller sätter geometriförinställningstyp. |
| [setShapeType(int value)](#setShapeType-int-) | Returnerar eller sätter geometriförinställningstyp. |
| [getTextFrame()](#getTextFrame--) | Returnerar text för SmartArt shape. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Returnerar eller sätter geometriförinställningstyp. Obs: vid värdeförändring återställs alla justeringsvärden till sina standardvärden. Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Returnerar:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Returnerar eller sätter geometriförinställningstyp. Obs: vid värdeförändring återställs alla justeringsvärden till sina standardvärden. Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Returnerar text för SmartArt shape. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)