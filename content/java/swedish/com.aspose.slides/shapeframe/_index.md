---
title: ShapeFrame
second_title: Aspose.Slides för Java API-referens
description: Representerar egenskaper för formramar.
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

Representerar formramens egenskaper.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Skapar nya egenskaper för en formram. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | Returnerar X-koordinaten för ramens övre vänstra hörn. |
| [getY()](#getY--) | Returnerar Y-koordinaten för ramens övre vänstra hörn. |
| [getWidth()](#getWidth--) | Returnerar bredden på en ram. |
| [getHeight()](#getHeight--) | Returnerar höjden på en ram. |
| [getRotation()](#getRotation--) | Returnerar antalet grader en ram roteras kring z-axeln. |
| [getCenterX()](#getCenterX--) | Returnerar X-koordinaten för ramens centrum. |
| [getCenterY()](#getCenterY--) | Returnerar Y-koordinaten för ramens centrum. |
| [getFlipH()](#getFlipH--) | Bestämmer om en ram är vänd horisontellt. |
| [getFlipV()](#getFlipV--) | Bestämmer om en ram är vänd vertikalt. |
| [getRectangle()](#getRectangle--) | Returnerar koordinaterna för en ram. |
| [deepClone()](#deepClone--) | Klonar |
| [cloneT()](#cloneT--) | Klonar. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet objekt. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet objekt. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Skapar nya egenskaper för en formram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för en ram. |
| y | float | Y-koordinaten för en ram. |
| width | float | Bredden på en ram. |
| height | float | Höjden på en ram. |
| flipH | byte | Sant om en ram är vänd horisontellt. |
| flipV | byte | Sant om en ram är vänd vertikalt. |
| rotationAngle | float | Antalet grader som en ram roteras. |

### getX() {#getX--}
```
public final float getX()
```

Returnerar X-koordinaten för ramens övre vänstra hörn. Skrivskyddad float.

**Returnerar:**
float
### getY() {#getY--}
```
public final float getY()
```

Returnerar Y-koordinaten för ramens övre vänstra hörn. Skrivskyddad float.

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

Returnerar antalet grader en ram roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skrivskyddad float.

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
public final Rectangle2D.Float getRectangle()
```

Returnerar koordinaterna för en ram. Skrivskyddad java.awt.geom.Rectangle2D.Float.

**Returnerar:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klonar

**Returnerar:**
java.lang.Object - Klonad formram.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Klonar.

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Klonad formram.
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

Returnerar ett värde som indikerar om denna instans är lika med ett angivet objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med denna instans. |

**Returnerar:**
boolean - **true** om obj är en ShapeFrame som har samma värde som denna instans; annars, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Returnerar ett värde som indikerar om denna instans är lika med ett angivet objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx att jämföra med denna instans. |

**Returnerar:**
boolean - **true** om value är en ShapeFrame som har samma värde som denna instans; annars, **false**.