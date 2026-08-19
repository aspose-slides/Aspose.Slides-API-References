---
title: IShapeFrame
second_title: Aspose.Slides för Java API-referens
description: Representerar egenskaperna för formramar.
type: docs
url: /sv/com.aspose.slides/ishapeframe/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Representerar egenskaperna för en formram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | Returnerar X-koordinaten för det övre vänstra hörnet av en ram. |
| [getY()](#getY--) | Returnerar Y-koordinaten för det övre vänstra hörnet av en ram. |
| [getWidth()](#getWidth--) | Returnerar bredden på en ram. |
| [getHeight()](#getHeight--) | Returnerar höjden på en ram. |
| [getRotation()](#getRotation--) | Returnerar antalet grader en ram är roterad runt z-axeln. |
| [getCenterX()](#getCenterX--) | Returnerar X-koordinaten för en rams centrum. |
| [getCenterY()](#getCenterY--) | Returnerar Y-koordinaten för en rams centrum. |
| [getFlipH()](#getFlipH--) | Avgör om en ram är speglad horisontellt. |
| [getFlipV()](#getFlipV--) | Avgör om en ram är speglad vertikalt. |
| [getRectangle()](#getRectangle--) | Returnerar koordinaterna för en ram. |
### getX() {#getX--}
```
public abstract float getX()
```

Returnerar X-koordinaten för det övre vänstra hörnet av en ram. Endast läsbar float.

**Returnerar:**
float
### getY() {#getY--}
```
public abstract float getY()
```

Returnerar Y-koordinaten för det övre vänstra hörnet av en ram. Endast läsbar float.

**Returnerar:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Returnerar bredden på en ram. Endast läsbar float.

**Returnerar:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Returnerar höjden på en ram. Endast läsbar float.

**Returnerar:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Returnerar antalet grader en ram är roterad runt z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde indikerar motursrotation. Endast läsbar float.

**Returnerar:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

Returnerar X-koordinaten för en rams centrum. Endast läsbar float.

**Returnerar:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

Returnerar Y-koordinaten för en rams centrum. Endast läsbar float.

**Returnerar:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

Avgör om en ram är speglad horisontellt. Endast läsbar [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

Avgör om en ram är speglad vertikalt. Endast läsbar [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```

Returnerar koordinaterna för en ram. Endast läsbar java.awt.geom.Rectangle2D.Float.

**Returnerar:**
java.awt.geom.Rectangle2D.Float