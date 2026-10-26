---
title: SmartArtShape
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar SmartArt-form
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

Representerar SmartArt-form
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapeType()](#getShapeType--) | Returnerar eller sätter geometripreset-typen. |
| [setShapeType(int value)](#setShapeType-int-) | Returnerar eller sätter geometripreset-typen. |
| [getTextFrame()](#getTextFrame--) | Returnerar texten för SmartArt-formen. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Returnerar eller sätter geometripreset-typen. Obs: vid värdeförändring återställs alla justeringsvärden till deras standardvärden. Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Returnerar:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Returnerar eller sätter geometripreset-typen. Obs: vid värdeförändring återställs alla justeringsvärden till deras standardvärden. Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Returnerar texten för SmartArt-formen. Endast läsning [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)