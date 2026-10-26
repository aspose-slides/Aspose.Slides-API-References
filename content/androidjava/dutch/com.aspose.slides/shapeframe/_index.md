---
title: ShapeFrame
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt de eigenschappen van shape frames voor.
type: docs
url: /nl/com.aspose.slides/shapeframe/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Stelt de eigenschappen van een shape-frame voor.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Maakt nieuwe shape-frame-eigenschappen aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getX()](#getX--) | Retourneert de X-coördinaat van de linkerbovenhoek van een frame. |
| [getY()](#getY--) | Retourneert de Y-coördinaat van de linkerbovenhoek van een frame. |
| [getWidth()](#getWidth--) | Retourneert de breedte van een frame. |
| [getHeight()](#getHeight--) | Retourneert de hoogte van een frame. |
| [getRotation()](#getRotation--) | Retourneert het aantal graden waarop een frame rond de z-as is geroteerd. |
| [getCenterX()](#getCenterX--) | Retourneert de X-coördinaat van het midden van een frame. |
| [getCenterY()](#getCenterY--) | Retourneert de Y-coördinaat van het midden van een frame. |
| [getFlipH()](#getFlipH--) | Bepaalt of een frame horizontaal is gespiegeld. |
| [getFlipV()](#getFlipV--) | Bepaalt of een frame verticaal is gespiegeld. |
| [getRectangle()](#getRectangle--) | Retourneert de coördinaten van een frame. |
| [deepClone()](#deepClone--) | Kopieert |
| [cloneT()](#cloneT--) | Kopieert. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Maakt nieuwe shape-frame-eigenschappen aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van een frame. |
| y | float | Y-coördinaat van een frame. |
| width | float | Breedte van een frame. |
| height | float | Hoogte van een frame. |
| flipH | byte | Waar als een frame horizontaal is gespiegeld. |
| flipV | byte | Waar als een frame verticaal is gespiegeld. |
| rotationAngle | float | Aantal graden waarop een frame is geroteerd. |

### getX() {#getX--}
```
public final float getX()
```

Retourneert de X-coördinaat van de linkerbovenhoek van een frame. Alleen-lezen float.

**Retour:**
float
### getY() {#getY--}
```
public final float getY()
```

Retourneert de Y-coördinaat van de linkerbovenhoek van een frame. Alleen-lezen float.

**Retour:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Retourneert de breedte van een frame. Alleen-lezen float.

**Retour:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Retourneert de hoogte van een frame. Alleen-lezen float.

**Retour:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Retourneert het aantal graden waarop een frame rond de z-as is geroteerd. Een positieve waarde duidt op een klokwijzerrotatie; een negatieve waarde duidt op een tegenklokrotatie. Alleen-lezen float.

**Retour:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Retourneert de X-coördinaat van het midden van een frame. Alleen-lezen float.

**Retour:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Retourneert de Y-coördinaat van het midden van een frame. Alleen-lezen float.

**Retour:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Bepaalt of een frame horizontaal is gespiegeld. Alleen-lezen [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Bepaalt of een frame verticaal is gespiegeld. Alleen-lezen [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Retourneert de coördinaten van een frame. Alleen-lezen android.graphics.RectF.

**Retour:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Kopieert

**Retour:**
java.lang.Object - Gekopieerd shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Kopieert.

**Retour:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Gekopieerd shape frame.
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Retour:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met deze instantie. |

**Retour:**
boolean - **true** als obj een ShapeFrame is die dezelfde waarde heeft als deze instantie; anders **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | De ShapeFRameEx om te vergelijken met deze instantie. |

**Retour:**
boolean - **true** als value een ShapeFrame is die dezelfde waarde heeft als deze instantie; anders **false**.