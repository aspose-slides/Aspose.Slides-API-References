---
title: ITableFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar formatet för en tabell.
type: docs
url: /sv/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Representerar formatet för en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returnerar ett objekt för tabellens fyllningsegenskaper. |
| [getTransparency()](#getTransparency--) | Hämtar eller anger genomskinligheten för fyllningsfärgen. |
| [setTransparency(float value)](#setTransparency-float-) | Hämtar eller anger genomskinligheten för fyllningsfärgen. |
| [getEffective()](#getEffective--) | Hämtar effektiva tabellformateringsegenskaper med arv och tillämpade tabellstilar. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Returnerar ett objekt för tabellens fyllningsegenskaper. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Hämtar eller anger genomskinligheten för fyllningsfärgen. Läs/skriv  float .

**Returnerar:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Hämtar eller anger genomskinligheten för fyllningsfärgen. Läs/skriv  float .

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