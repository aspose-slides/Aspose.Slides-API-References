---
title: ILineFillFormat
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: A vonalak kitöltésének tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/ilinefillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Represents properties for lines filling.
## Metódusok

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Visszaadja vagy beállítja a kitöltés típusát. |
| [setFillType(byte value)](#setFillType-byte-) | Visszaadja vagy beállítja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja a szilárd kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenet kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a mintás kitöltés formátumát. |
| [getRotateWithShape()](#getRotateWithShape--) | Megállapítja, hogy a kitöltést az alakzattal együtt kell-e elforgatni. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Megállapítja, hogy a kitöltést az alakzattal együtt kell-e elforgatni. |
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


Visszaadja a szilárd kitöltés színét. Csak olvasás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Visszaadja a színátmenet kitöltés formátumát. Csak olvasás [IGradientFormat](../../com.aspose.slides/igradientformat).

**Visszatér:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Visszaadja a mintás kitöltés formátumát. Csak olvasás [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Visszatér:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Megállapítja, hogy a kitöltést az alakzattal együtt kell-e elforgatni. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Megállapítja, hogy a kitöltést az alakzattal együtt kell-e elforgatni. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |