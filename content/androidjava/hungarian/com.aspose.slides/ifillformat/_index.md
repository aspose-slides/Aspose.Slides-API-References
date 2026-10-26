---
title: IFillFormat
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Kitöltési formázási beállításokat képvisel.
type: docs
url: /hu/com.aspose.slides/ifillformat/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

A kitöltési formázási beállításokat képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillType()](#getFillType--) | Visszaadja vagy beállítja a kitöltés típusát. |
| [setFillType(byte value)](#setFillType-byte-) | Visszaadja vagy beállítja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja a kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenetes kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a mintás kitöltés formátumát. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Visszaadja a képes kitöltés formátumát. |
| [getRotateWithShape()](#getRotateWithShape--) | Megállapítja, hogy a kitöltést a forma forgatása befolyásolja-e. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Megállapítja, hogy a kitöltést a forma forgatása befolyásolja-e. |
| [getEffective()](#getEffective--) | Lekéri a hatékony kitöltési formázási adatokat az öröklődés alkalmazásával. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Visszaadja vagy beállítja a kitöltés típusát. Olvasás/írás [FillType](../../com.aspose.slides/filltype).

**Visszatérési érték:**
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


Visszaadja a kitöltés színét. Csak olvasás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Visszaadja a színátmenetes kitöltés formátumát. Csak olvasás [IGradientFormat](../../com.aspose.slides/igradientformat).

**Visszatérési érték:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Visszaadja a mintás kitöltés formátumát. Csak olvasás [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Visszatérési érték:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Visszaadja a képes kitöltés formátumát. Csak olvasás [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatérési érték:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Megállapítja, hogy a kitöltést a forma forgatása befolyásolja-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Megállapítja, hogy a kitöltést a forma forgatása befolyásolja-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Lekéri a hatékony kitöltési formázási adatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).