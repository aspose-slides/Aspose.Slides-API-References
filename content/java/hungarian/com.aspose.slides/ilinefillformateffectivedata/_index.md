---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides Java API Referencia
description: Megváltoztathatatlan objektum, amely hatékony vonalkitöltő tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/ilinefillformateffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Megváltoztathatatlan objektum, amely hatékony vonalkitöltő tulajdonságokat tartalmaz.

--------------------

Ez az interfész a [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) részeként használható.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFillType()](#getFillType--) | Visszaadja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja egy szilárd kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenet kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a minta kitöltés formátumát. |
| [getRotateWithShape()](#getRotateWithShape--) | Megállapítja, hogy a kitöltést egy alakzattal együtt kell-e elforgatni. |
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

Visszaadja egy szilárd kitöltés színét. Csak olvasható java.awt.Color.

**Visszatér:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Visszaadja a színátmenet kitöltés formátumát. Csak olvasható [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Visszatér:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Visszaadja a minta kitöltés formátumát. Csak olvasható [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Visszatér:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Megállapítja, hogy a kitöltést egy alakzattal együtt kell-e elforgatni. Csak olvasható boolean.

**Visszatér:**
boolean