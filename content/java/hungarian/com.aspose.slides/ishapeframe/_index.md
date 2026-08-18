---
title: IShapeFrame
second_title: Aspose.Slides Java API referenciája
description: A forma keret tulajdonságait ábrázolja.
type: docs
url: /hu/com.aspose.slides/ishapeframe/
---
**Minden implementált interfész:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

A forma keret tulajdonságait ábrázolja.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getX()](#getX--) | Visszaadja egy keret bal felső sarkának X koordinátáját. |
| [getY()](#getY--) | Visszaadja egy keret bal felső sarkának Y koordinátáját. |
| [getWidth()](#getWidth--) | Visszaadja egy keret szélességét. |
| [getHeight()](#getHeight--) | Visszaadja egy keret magasságát. |
| [getRotation()](#getRotation--) | Visszaadja a keret z-tengely körüli forgatásának fokszámát. |
| [getCenterX()](#getCenterX--) | Visszaadja egy keret középpontjának X koordinátáját. |
| [getCenterY()](#getCenterY--) | Visszaadja egy keret középpontjának Y koordinátáját. |
| [getFlipH()](#getFlipH--) | Megállapítja, hogy egy keret vízszintesen tükrözött-e. |
| [getFlipV()](#getFlipV--) | Megállapítja, hogy egy keret függőlegesen tükrözött-e. |
| [getRectangle()](#getRectangle--) | Visszaadja egy keret koordinátáit. |
### getX() {#getX--}
```
public abstract float getX()
```


Visszaadja egy keret bal felső sarkának X koordinátáját. Csak olvasható float.

**Visszatér:**
float
### getY() {#getY--}
```
public abstract float getY()
```


Visszaadja egy keret bal felső sarkának Y koordinátáját. Csak olvasható float.

**Visszatér:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Visszaadja egy keret szélességét. Csak olvasható float.

**Visszatér:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Visszaadja egy keret magasságát. Csak olvasható float.

**Visszatér:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Visszaadja a keret z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellentétes irányú forgást. Csak olvasható float.

**Visszatér:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


Visszaadja egy keret középpontjának X koordinátáját. Csak olvasható float.

**Visszatér:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


Visszaadja egy keret középpontjának Y koordinátáját. Csak olvasható float.

**Visszatér:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


Megállapítja, hogy egy keret vízszintesen tükrözött-e. Csak olvasható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


Megállapítja, hogy egy keret függőlegesen tükrözött-e. Csak olvasható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```


Visszaadja egy keret koordinátáit. Csak olvasható java.awt.geom.Rectangle2D.Float.

**Visszatér:**
java.awt.geom.Rectangle2D.Float