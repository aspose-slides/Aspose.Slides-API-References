---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Képviseli egy állítható rajzolási segédvonalat.
type: docs
url: /hu/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Képviseli egy állítható rajzolási segédvonalat.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOrientation()](#getOrientation--) | Visszaadja vagy beállítja a rajzolási segédvonal orientációját. |
| [setOrientation(byte value)](#setOrientation-byte-) | Visszaadja vagy beállítja a rajzolási segédvonal orientációját. |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja a rajzolási segédvonal pozícióját pontokban a dia bal felső sarkától. |
| [setPosition(float value)](#setPosition-float-) | Visszaadja vagy beállítja a rajzolási segédvonal pozícióját pontokban a dia bal felső sarkától. |
| [getColor()](#getColor--) | Visszaadja vagy beállítja a rajzolási segédvonal színét. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Visszaadja vagy beállítja a rajzolási segédvonal színét. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

Visszaadja vagy beállítja a rajzolási segédvonal orientációját. Olvasás/írás [Orientation](../../com.aspose.slides/orientation).

**Visszatérési érték:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

Visszaadja vagy beállítja a rajzolási segédvonal orientációját. Olvasás/írás [Orientation](../../com.aspose.slides/orientation).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Visszaadja vagy beállítja a rajzolási segédvonal pozícióját pontokban a dia bal felső sarkától. Olvasás/írás float.

--------------------

A tipikus értéktartomány nulla és a dia magassága között egy vízszintes segédvonal esetén, valamint nulla és a dia szélessége között egy függőleges segédvonal esetén.

**Visszatérési érték:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Visszaadja vagy beállítja a rajzolási segédvonal pozícióját pontokban a dia bal felső sarkától. Olvasás/írás float.

--------------------

A tipikus értéktartomány nulla és a dia magassága között egy vízszintes segédvonal esetén, valamint nulla és a dia szélessége között egy függőleges segédvonal esetén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

Visszaadja vagy beállítja a rajzolási segédvonal színét. Olvasás/írás java.awt.Color.

**Visszatérési érték:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Visszaadja vagy beállítja a rajzolási segédvonal színét. Olvasás/írás java.awt.Color.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.Color |  |