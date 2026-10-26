---
title: ILineFillFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar egenskaper för linjefyllning.
type: docs
url: /sv/com.aspose.slides/ilinefillformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Representerar egenskaper för linjefyllning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillType()](#getFillType--) | Returnerar eller anger fyllningstypen. |
| [setFillType(byte value)](#setFillType-byte-) | Returnerar eller anger fyllningstypen. |
| [getSolidFillColor()](#getSolidFillColor--) | Returnerar färgen på en solid fyllning. |
| [getGradientFormat()](#getGradientFormat--) | Returnerar formatet för gradientfyllning. |
| [getPatternFormat()](#getPatternFormat--) | Returnerar formatet för mönsterfyllning. |
| [getRotateWithShape()](#getRotateWithShape--) | Bestämmer om fyllningen ska roteras med en form. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Bestämmer om fyllningen ska roteras med en form. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Returnerar eller anger fyllningstypen. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Returnerar:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

Returnerar eller anger fyllningstypen. Läs/skriv [FillType](../../com.aspose.slides/filltype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

Returnerar färgen på en solid fyllning. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

Returnerar formatet för gradientfyllning. Endast läsning [IGradientFormat](../../com.aspose.slides/igradientformat).

**Returnerar:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

Returnerar formatet för mönsterfyllning. Endast läsning [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Returnerar:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

Bestämmer om fyllningen ska roteras med en form. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

Bestämmer om fyllningen ska roteras med en form. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |