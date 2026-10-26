---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Megváltoztathatatlan objektum, amely hatékony vonalkitöltési tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/ilinefillformateffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Immutable objektum, amely hatékony vonalkitöltési tulajdonságokat tartalmaz.

--------------------

Ez az interfész a [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) részeként használatos.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFillType()](#getFillType--) | Visszaadja a kitöltés típusát. |
| [getSolidFillColor()](#getSolidFillColor--) | Visszaadja egy szilárd kitöltés színét. |
| [getGradientFormat()](#getGradientFormat--) | Visszaadja a színátmenetes kitöltés formátumát. |
| [getPatternFormat()](#getPatternFormat--) | Visszaadja a mintás kitöltés formátumát. |
| [getRotateWithShape()](#getRotateWithShape--) | Meghatározza, hogy a kitöltést egy alakzattal kell-e forgatni. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Visszaadja a kitöltés típusát. Csak olvasható [FillType](../../com.aspose.slides/filltype).

**Visszatér:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

Visszaadja egy szilárd kitöltés színét. Csak olvasható java.lang.Integer.

**Visszatér:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Visszaadja a színátmenetes kitöltés formátumát. Csak olvasható [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Visszatér:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Visszaadja a mintás kitöltés formátumát. Csak olvasható [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Visszatér:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Meghatározza, hogy a kitöltést egy alakzattal kell-e forgatni. Csak olvasható boolean.

**Visszatér:**
boolean