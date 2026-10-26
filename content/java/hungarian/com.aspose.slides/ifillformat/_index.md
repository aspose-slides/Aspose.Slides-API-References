---
title: IFillFormat
second_title: Aspose.Slides for Java API Referenciája
description: Kitöltési formázási beállításokat reprezentál.
type: docs
url: /hu/com.aspose.slides/ifillformat/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Egy kitöltési formázási beállítást reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillType()](#getFillType--) | Visszaadja vagy beállítja a kitöltés típusát. |
| [setFillType(byte value)](#setFillType-byte-) | Visszaadja vagy beállítja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja a kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenetes kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a minta kitöltés formátumát. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Visszaadja a kép kitöltés formátumát. |
| [getRotateWithShape()](#getRotateWithShape--) | Megállapítja, hogy a kitöltést az alakzattal együtt kell-e forgatni. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Megállapítja, hogy a kitöltést az alakzattal együtt kell-e forgatni. |
| [getEffective()](#getEffective--) | Megkapja a hatékony kitöltési formázási adatokat az öröklődés alkalmazásával. |
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

Visszaadja a kitöltés színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

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

Visszaadja a minta kitöltés formátumát. Csak olvasható [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Visszatér:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

Visszaadja a kép kitöltés formátumát. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Megállapítja, hogy a kitöltést az alakzattal együtt kell-e forgatni. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Megállapítja, hogy a kitöltést az alakzattal együtt kell-e forgatni. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

Megkapja a hatékony kitöltési formázási adatokat az öröklődés alkalmazásával.

**Visszatér:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).