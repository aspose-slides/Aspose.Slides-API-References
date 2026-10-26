---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Java API Referencia
description: Módosíthatatlan objektum, amely a hatékony kitöltési formázási tulajdonságokat tartalmazza.
type: docs
url: /hu/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Módosíthatatlan objektum, amely a hatékony kitöltési formázási tulajdonságokat tartalmazza.

--------------------

Ez az interfész a [IFillFormat](../../com.aspose.slides/ifillformat) interfészzel együtt használatos a hatékony formázási értékek visszaadásához, öröklődés alkalmazásával.
## Methods

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Visszaadja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja a kitöltőszínt. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Lekéri a színpaletta által definiált kitöltőszínt. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenet kitöltési formátumot. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a mintás kitöltési formátumot. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Visszaadja a kép kitöltési formátumot. |
| [getRotateWithShape()](#getRotateWithShape--) | Meghatározza, hogy a kitöltést a forma forgatja-e. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Visszaadja a kitöltés típusát. Csak olvasható [FillType](../../com.aspose.slides/filltype).

**Visszatér:**  
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

Visszaadja a kitöltőszínt. Csak olvasható java.awt.Color.

**Visszatér:**  
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

Lekéri a színpaletta által definiált kitöltőszínt. A [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) érték azt jelzi, hogy a SolidFillColor (\#getSolidFillColor.getSolidFillColor) nem színséma szín. Csak olvasható [SchemeColor](../../com.aspose.slides/schemecolor).

**Visszatér:**  
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Visszaadja a színátmenet kitöltési formátumot. Csak olvasható [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Visszatér:**  
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Visszaadja a mintás kitöltési formátumot. Csak olvasható [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Visszatér:**  
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

Visszaadja a kép kitöltési formátumot. Csak olvasható [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Visszatér:**  
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Meghatározza, hogy a kitöltést a forma forgatja-e. Csak olvasható boolean.

**Visszatér:**  
boolean