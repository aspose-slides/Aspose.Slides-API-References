---
title: ShapeFrame
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le proprietà dei frame della forma.
type: docs
url: /it/com.aspose.slides/shapeframe/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Rappresenta le proprietà del frame della forma.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Crea le proprietà del frame della forma. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getX()](#getX--) | Restituisce la coordinata X dell'angolo superiore sinistro di un frame. |
| [getY()](#getY--) | Restituisce la coordinata Y dell'angolo superiore sinistro di un frame. |
| [getWidth()](#getWidth--) | Restituisce la larghezza di un frame. |
| [getHeight()](#getHeight--) | Restituisce l'altezza di un frame. |
| [getRotation()](#getRotation--) | Restituisce il numero di gradi di rotazione di un frame attorno all'asse z. |
| [getCenterX()](#getCenterX--) | Restituisce la coordinata X del centro di un frame. |
| [getCenterY()](#getCenterY--) | Restituisce la coordinata Y del centro di un frame. |
| [getFlipH()](#getFlipH--) | Determina se un frame è capovolto orizzontalmente. |
| [getFlipV()](#getFlipV--) | Determina se un frame è capovolto verticalmente. |
| [getRectangle()](#getRectangle--) | Restituisce le coordinate di un frame. |
| [deepClone()](#deepClone--) | Clona |
| [cloneT()](#cloneT--) | Clona. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un oggetto specificato. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Restituisce un valore che indica se questa istanza è uguale a un oggetto specificato. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Crea le proprietà del frame della forma.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | Coordinata X di un frame. |
| y | float | Coordinata Y di un frame. |
| width | float | Larghezza di un frame. |
| height | float | Altezza di un frame. |
| flipH | byte | True se un frame è capovolto orizzontalmente. |
| flipV | byte | True se un frame è capovolto verticalmente. |
| rotationAngle | float | Numero di gradi di rotazione di un frame. |
### getX() {#getX--}
```
public final float getX()
```

Restituisce la coordinata X dell'angolo superiore sinistro di un frame. Solo lettura float.

**Restituisce:**
float
### getY() {#getY--}
```
public final float getY()
```

Restituisce la coordinata Y dell'angolo superiore sinistro di un frame. Solo lettura float.

**Restituisce:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Restituisce la larghezza di un frame. Solo lettura float.

**Restituisce:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Restituisce l'altezza di un frame. Solo lettura float.

**Restituisce:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Restituisce il numero di gradi di rotazione di un frame attorno all'asse z. Un valore positivo indica una rotazione in senso orario; un valore negativo indica una rotazione in senso antiorario. Solo lettura float.

**Restituisce:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Restituisce la coordinata X del centro di un frame. Solo lettura float.

**Restituisce:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Restituisce la coordinata Y del centro di un frame. Solo lettura float.

**Restituisce:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Determina se un frame è capovolto orizzontalmente. Solo lettura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Determina se un frame è capovolto verticalmente. Solo lettura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Restituisce le coordinate di un frame. Solo lettura android.graphics.RectF.

**Restituisce:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Clona

**Restituisce:**
java.lang.Object - Frame della forma clonato.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Clona.

**Restituisce:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Frame della forma clonato.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Restituisce:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Restituisce un valore che indica se questa istanza è uguale a un oggetto specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare con questa istanza. |

**Restituisce:**
boolean - **true** se obj è uno ShapeFrame che ha lo stesso valore di questa istanza; altrimenti, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Restituisce un valore che indica se questa istanza è uguale a un oggetto specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Lo ShapeFRameEx da confrontare con questa istanza. |

**Restituisce:**
boolean - **true** se value è uno ShapeFrame che ha lo stesso valore di questa istanza; altrimenti, **false**.