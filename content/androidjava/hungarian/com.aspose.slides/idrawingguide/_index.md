---
title: IDrawingGuide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an adjustable drawing guide.
type: docs
url: /hu/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Állítható rajzvezetőt képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getOrientation()](#getOrientation--) | Visszaadja vagy beállítja a rajzvezető tájolását. |
| [setOrientation(byte value)](#setOrientation-byte-) | Visszaadja vagy beállítja a rajzvezető tájolását. |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja a rajzvezető pozícióját pontokban a dia bal felső sarkától. |
| [setPosition(float value)](#setPosition-float-) | Visszaadja vagy beállítja a rajzvezető pozícióját pontokban a dia bal felső sarkától. |
| [getColor()](#getColor--) | Visszaadja vagy beállítja a rajzvezető színét. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Visszaadja vagy beállítja a rajzvezető színét. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Visszaadja vagy beállítja a rajzvezető tájolását. Olvasás/írás [Orientation](../../com.aspose.slides/orientation).

**Visszatérési érték:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Visszaadja vagy beállítja a rajzvezető tájolását. Olvasás/írás [Orientation](../../com.aspose.slides/orientation).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Visszaadja vagy beállítja a rajzvezető pozícióját pontokban a dia bal felső sarkától. Olvasás/írás float.

--------------------

A tipikus értéktartomány nulla és a dia magassága között egy vízszintes segéd esetén, illetve nulla és a dia szélessége között egy függőleges segéd esetén.

**Visszatérési érték:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Visszaadja vagy beállítja a rajzvezető pozícióját pontokban a dia bal felső sarkától. Olvasás/írás float.

--------------------

A tipikus értéktartomány nulla és a dia magassága között egy vízszintes segéd esetén, illetve nulla és a dia szélessége között egy függőleges segéd esetén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Visszaadja vagy beállítja a rajzvezető színét. Olvasás/írás java.lang.Integer.

**Visszatérési érték:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Visszaadja vagy beállítja a rajzvezető színét. Olvasás/írás java.lang.Integer.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Integer |  |