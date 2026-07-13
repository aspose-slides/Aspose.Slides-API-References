---
title: ShapeFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar egenskaper för shape frames.
type: docs
url: /sv/com.aspose.slides/shapeframe/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Representerar egenskaperna för en shape frame.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Skapar nya shape frame-egenskaper. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | Returnerar X-koordinaten för den övre vänstra hörnet av en ram. |
| [getY()](#getY--) | Returnerar Y-koordinaten för den övre vänstra hörnet av en ram. |
| [getWidth()](#getWidth--) | Returnerar bredden på en ram. |
| [getHeight()](#getHeight--) | Returnerar höjden på en ram. |
| [getRotation()](#getRotation--) | Returnerar antalet grader som en ram är roterad kring Z-axeln. |
| [getCenterX()](#getCenterX--) | Returnerar X-koordinaten för ramens centrum. |
| [getCenterY()](#getCenterY--) | Returnerar Y-koordinaten för ramens centrum. |
| [getFlipH()](#getFlipH--) | Bestämmer om en ram är vänd horisontellt. |
| [getFlipV()](#getFlipV--) | Bestämmer om en ram är vänd vertikalt. |
| [getRectangle()](#getRectangle--) | Returnerar koordinaterna för en ram. |
| [deepClone()](#deepClone--) | Klonar |
| [cloneT()](#cloneT--) | Klonar. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat objekt. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat objekt. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Skapar nya shape frame-egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för en ram. |
| y | float | Y-koordinaten för en ram. |
| width | float | Bredden på en ram. |
| height | float | Höjden på en ram. |
| flipH | byte | Sant om en ram är vänd horisontellt. |
| flipV | byte | Sant om en ram är vänd vertikalt. |
| rotationAngle | float | Antalet grader som en ram är roterad. |

### getX() {#getX--}
```
public final float getX()
```

Returnerar X-koordinaten för den övre vänstra hörnet av en ram. Skrivskyddad float.

**Returnerar:**
float
### getY() {#getY--}
```
public final float getY()
```

Returnerar Y-koordinaten för den övre vänstra hörnet av en ram. Skrivskyddad float.

**Returnerar:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Returnerar bredden på en ram. Skrivskyddad float.

**Returnerar:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Returnerar höjden på en ram. Skrivskyddad float.

**Returnerar:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Returnerar antalet grader som en ram är roterad kring Z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skrivskyddad float.

**Returnerar:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Returnerar X-koordinaten för ramens centrum. Skrivskyddad float.

**Returnerar:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Returnerar Y-koordinaten för ramens centrum. Skrivskyddad float.

**Returnerar:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Bestämmer om en ram är vänd horisontellt. Skrivskyddad [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Bestämmer om en ram är vänd vertikalt. Skrivskyddad [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Returnerar koordinaterna för en ram. Skrivskyddad android.graphics.RectF.

**Returnerar:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klonar

**Returnerar:**
java.lang.Object - Klonad shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Klonar.

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Klonad shape frame.
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Returnerar:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med denna instans. |

**Returnerar:**
boolean - **true** om obj är en ShapeFrame som har samma värde som denna instans; annars **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx att jämföra med denna instans. |

**Returnerar:**
boolean - **true** om value är en ShapeFrame som har samma värde som denna instans; annars **false**.