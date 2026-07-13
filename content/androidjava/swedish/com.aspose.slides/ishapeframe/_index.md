---
title: IShapeFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar egenskaper för formramar.
type: docs
url: /sv/com.aspose.slides/ishapeframe/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Representerar formramens egenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | Returnerar X-koordinaten för övre vänstra hörnet på en ram. |
| [getY()](#getY--) | Returnerar Y-koordinaten för övre vänstra hörnet på en ram. |
| [getWidth()](#getWidth--) | Returnerar bredden på en ram. |
| [getHeight()](#getHeight--) | Returnerar höjden på en ram. |
| [getRotation()](#getRotation--) | Returnerar antalet grader en ram roteras runt z-axeln. |
| [getCenterX()](#getCenterX--) | Returnerar X-koordinaten för en rams mittpunkt. |
| [getCenterY()](#getCenterY--) | Returnerar Y-koordinaten för en rams mittpunkt. |
| [getFlipH()](#getFlipH--) | Avgör om en ram är speglad horisontellt. |
| [getFlipV()](#getFlipV--) | Avgör om en ram är speglad vertikalt. |
| [getRectangle()](#getRectangle--) | Returnerar koordinaterna för en ram. |
### getX() {#getX--}
```
public abstract float getX()
```

Returnerar X-koordinaten för övre vänstra hörnet på en ram. Skrivskyddad float.

**Returnerar:**
float
### getY() {#getY--}
```
public abstract float getY()
```

Returnerar Y-koordinaten för övre vänstra hörnet på en ram. Skrivskyddad float.

**Returnerar:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Returnerar bredden på en ram. Skrivskyddad float.

**Returnerar:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Returnerar höjden på en ram. Skrivskyddad float.

**Returnerar:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Returnerar antalet grader en ram roteras runt z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skrivskyddad float.

**Returnerar:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

Returnerar X-koordinaten för en rams mittpunkt. Skrivskyddad float.

**Returnerar:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

Returnerar Y-koordinaten för en rams mittpunkt. Skrivskyddad float.

**Returnerar:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

Avgör om en ram är speglad horisontellt. Skrivskyddad [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

Avgör om en ram är speglad vertikalt. Skrivskyddad [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```

Returnerar koordinaterna för en ram. Skrivskyddad android.graphics.RectF.

**Returnerar:**
android.graphics.RectF