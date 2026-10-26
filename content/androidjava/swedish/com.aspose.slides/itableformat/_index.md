---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table.
type: docs
url: /sv/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Representerar formatet för en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returnerar ett objekt för tabellfyllnings egenskaper. |
| [getTransparency()](#getTransparency--) | Hämtar eller anger transparensen för fyllningsfärgen. |
| [setTransparency(float value)](#setTransparency-float-) | Hämtar eller anger transparensen för fyllningsfärgen. |
| [getEffective()](#getEffective--) | Hämtar effektiva tabellformateringsegenskaper med arv och tillämpade tabellstilar. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Returnerar ett objekt för tabellfyllnings egenskaper. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Hämtar eller anger transparensen för fyllningsfärgen. Läs/skriv  float .

**Returnerar:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Hämtar eller anger transparensen för fyllningsfärgen. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Hämtar effektiva tabellformateringsegenskaper med arv och tillämpade tabellstilar.

**Returnerar:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - En [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).