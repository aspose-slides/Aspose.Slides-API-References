---
title: ILineFillFormat
second_title: Aspose.Slides for Java API referencia
description: A vonalak kitöltésének tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/ilinefillformat/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

A vonalak kitöltésének tulajdonságait képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillType()](#getFillType--) | Visszaadja vagy beállítja a kitöltés típusát. |
| [setFillType(byte value)](#setFillType-byte-) | Visszaadja vagy beállítja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja a szilárd kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenetes kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a mintás kitöltés formátumát. |
| [getRotateWithShape()](#getRotateWithShape--) | Megállapítja, hogy a kitöltést el kell-e forgatni a formával. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Megállapítja, hogy a kitöltést el kell-e forgatni a formával. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Visszaadja vagy beállítja a kitöltés típusát. Olvasás/írás [FillType](../../com.aspose.slides/filltype).

**Visszatér:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Visszaadja vagy beállítja a kitöltés típusát. Olvasás/írás [FillType](../../com.aspose.slides/filltype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Visszaadja a szilárd kitöltés színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Visszaadja a színátmenetes kitöltés formátumát. Csak olvasható [IGradientFormat](../../com.aspose.slides/igradientformat).

**Visszatér:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Visszaadja a mintás kitöltés formátumát. Csak olvasható [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Visszatér:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Megállapítja, hogy a kitöltést el kell-e forgatni a formával. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Megállapítja, hogy a kitöltést el kell-e forgatni a formával. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |