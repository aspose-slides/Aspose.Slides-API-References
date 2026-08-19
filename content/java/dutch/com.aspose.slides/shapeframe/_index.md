---
title: ShapeFrame
second_title: Aspose.Slides voor Java API-referentie
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

Stelt de eigenschappen van een shape frame voor.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Maakt nieuwe shape frame-eigenschappen aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getX()](#getX--) | Retourneert de X-coördinaat van de linkerbovenhoek van een frame. |
| [getY()](#getY--) | Retourneert de Y-coördinaat van de linkerbovenhoek van een frame. |
| [getWidth()](#getWidth--) | Retourneert de breedte van een frame. |
| [getHeight()](#getHeight--) | Retourneert de hoogte van een frame. |
| [getRotation()](#getRotation--) | Retourneert het aantal graden waarmee een frame om de z-as is geroteerd. |
| [getCenterX()](#getCenterX--) | Retourneert de X-coördinaat van het centrum van een frame. |
| [getCenterY()](#getCenterY--) | Retourneert de Y-coördinaat van het centrum van een frame. |
| [getFlipH()](#getFlipH--) | Bepaalt of een frame horizontaal is omgeklapt. |
| [getFlipV()](#getFlipV--) | Bepaalt of een frame verticaal is omgeklapt. |
| [getRectangle()](#getRectangle--) | Retourneert de coördinaten van een frame. |
| [deepClone()](#deepClone--) | Kloont |
| [cloneT()](#cloneT--) | Kloont. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


Maakt nieuwe shape frame-eigenschappen aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van een frame. |
| y | float | Y-coördinaat van een frame. |
| width | float | Breedte van een frame. |
| height | float | Hoogte van een frame. |
| flipH | byte | True als een frame horizontaal is omgeklapt. |
| flipV | byte | True als een frame verticaal is omgeklapt. |
| rotationAngle | float | Aantal graden waarmee een frame is geroteerd. |

### getX() {#getX--}
```
public final float getX()
```


Retourneert de X-coördinaat van de linkerbovenhoek van een frame. Alleen-lezen float.

**Retourneert:**
float
### getY() {#getY--}
```
public final float getY()
```


Retourneert de Y-coördinaat van de linkerbovenhoek van een frame. Alleen-lezen float.

**Retourneert:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Retourneert de breedte van een frame. Alleen-lezen float.

**Retourneert:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Retourneert de hoogte van een frame. Alleen-lezen float.

**Retourneert:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Retourneert het aantal graden waarmee een frame om de z-as is geroteerd. Een positieve waarde geeft een rotatie met de klok mee aan; een negatieve waarde geeft een rotatie tegen de klok in aan. Alleen-lezen float.

**Retourneert:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Retourneert de X-coördinaat van het centrum van een frame. Alleen-lezen float.

**Retourneert:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Retourneert de Y-coördinaat van het centrum van een frame. Alleen-lezen float.

**Retourneert:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


Bepaalt of een frame horizontaal is omgeklapt. Alleen-lezen [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


Bepaalt of een frame verticaal is omgeklapt. Alleen-lezen [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```


Retourneert de coördinaten van een frame. Alleen-lezen java.awt.geom.Rectangle2D.Float.

**Retourneert:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Kloont

**Retourneert:**
java.lang.Object - Gekloond shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


Kloont.

**Retourneert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Gekloond shape frame.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Retourneert:**
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

**Retourneert:**
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

**Retourneert:**
boolean - **true** als value een ShapeFrame is die dezelfde waarde heeft als deze instantie; anders **false**.