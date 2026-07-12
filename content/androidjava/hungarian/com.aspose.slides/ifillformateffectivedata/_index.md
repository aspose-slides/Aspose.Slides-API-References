---
title: IFillFormatEffectiveData
second_title: Aspose.Slides Androidra a Java API referenciája
description: Megváltoztathatatlan objektum, amely a tényleges kitöltési formázási tulajdonságokat tartalmazza.
type: docs
url: /hu/com.aspose.slides/ifillformateffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Megváltoztathatatlan objektum, amely a tényleges kitöltési formázási tulajdonságokat tartalmazza.

--------------------

Ez a csatoló a [IFillFormat](../../com.aspose.slides/ifillformat) csatolóval együtt használható a tényleges formázási értékek visszaadására, öröklődéssel alkalmazva.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFillType()](#getFillType--) | Visszaadja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja a kitöltés színét. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Lekéri a színsémával definiált kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenetes kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a mintás kitöltés formátumát. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Visszaadja a képes kitöltés formátumát. |
| [getRotateWithShape()](#getRotateWithShape--) | Meghatározza, hogy a kitöltést a formával együtt kell-e elforgatni. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Visszaadja a kitöltés típusát. Csak olvasható [FillType](../../com.aspose.slides/filltype).

**Visszatérési érték:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

Visszaadja a kitöltés színét. Csak olvasható java.lang.Integer.

**Visszatérési érték:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

Lekéri a színsémával definiált kitöltés színét. A [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) érték azt jelzi, hogy a SolidFillColor (\#getSolidFillColor.getSolidFillColor) nem színséma szín. Csak olvasható [SchemeColor](../../com.aspose.slides/schemecolor).

**Visszatérési érték:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Visszaadja a színátmenetes kitöltés formátumát. Csak olvasható [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Visszatérési érték:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Visszaadja a mintás kitöltés formátumát. Csak olvasható [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Visszatérési érték:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

Visszaadja a képes kitöltés formátumát. Csak olvasható [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Visszatérési érték:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Meghatározza, hogy a kitöltést a formával együtt kell-e elforgatni. Csak olvasható boolean.

**Visszatérési érték:**
boolean