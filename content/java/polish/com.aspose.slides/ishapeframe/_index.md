---
title: IShapeFrame
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje właściwości ramek kształtu.
type: docs
url: /pl/com.aspose.slides/ishapeframe/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Reprezentuje właściwości ramki kształtu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getX()](#getX--) | Zwraca współrzędną X lewego górnego rogu ramki. |
| [getY()](#getY--) | Zwraca współrzędną Y lewego górnego rogu ramki. |
| [getWidth()](#getWidth--) | Zwraca szerokość ramki. |
| [getHeight()](#getHeight--) | Zwraca wysokość ramki. |
| [getRotation()](#getRotation--) | Zwraca liczbę stopni, o które ramka jest obrócona wokół osi z. |
| [getCenterX()](#getCenterX--) | Zwraca współrzędną X środka ramki. |
| [getCenterY()](#getCenterY--) | Zwraca współrzędną Y środka ramki. |
| [getFlipH()](#getFlipH--) | Określa, czy ramka jest odbita w poziomie. |
| [getFlipV()](#getFlipV--) | Określa, czy ramka jest odbita w pionie. |
| [getRectangle()](#getRectangle--) | Zwraca współrzędne ramki. |
### getX() {#getX--}
```
public abstract float getX()
```

Zwraca współrzędną X lewego górnego rogu ramki. Tylko do odczytu float.

**Zwraca:**
float
### getY() {#getY--}
```
public abstract float getY()
```

Zwraca współrzędną Y lewego górnego rogu ramki. Tylko do odczytu float.

**Zwraca:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Zwraca szerokość ramki. Tylko do odczytu float.

**Zwraca:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Zwraca wysokość ramki. Tylko do odczytu float.

**Zwraca:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Zwraca liczbę stopni, o które ramka jest obrócona wokół osi z. Dodatnia wartość wskazuje obrót zgodny z ruchem wskazówek zegara; ujemna wartość wskazuje obrót przeciwny do ruchu wskazówek zegara. Tylko do odczytu float.

**Zwraca:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

Zwraca współrzędną X środka ramki. Tylko do odczytu float.

**Zwraca:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

Zwraca współrzędną Y środka ramki. Tylko do odczytu float.

**Zwraca:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

Określa, czy ramka jest odbita w poziomie. Tylko do odczytu [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

Określa, czy ramka jest odbita w pionie. Tylko do odczytu [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```

Zwraca współrzędne ramki. Tylko do odczytu java.awt.geom.Rectangle2D.Float.

**Zwraca:**
java.awt.geom.Rectangle2D.Float