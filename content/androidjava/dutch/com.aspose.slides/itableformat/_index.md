---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table.
type: docs
url: /nl/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Beschrijft het formaat van een tabel.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retourneert een object met tabelvullingseigenschappen. |
| [getTransparency()](#getTransparency--) | Haalt de transparantie van de vulkleur op of stelt deze in. |
| [setTransparency(float value)](#setTransparency-float-) | Haalt de transparantie van de vulkleur op of stelt deze in. |
| [getEffective()](#getEffective--) | Haalt effectieve tabelindelings-eigenschappen op met overerving en toegepaste tabelstijlen. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Retourneert een object met tabelvullingseigenschappen. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Haalt de transparantie van de vulkleur op of stelt deze in. Lezen/Schrijven  float .

**Retourneert:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Haalt de transparantie van de vulkleur op of stelt deze in. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Haalt effectieve tabelindelings-eigenschappen op met overerving en toegepaste tabelstijlen.

**Retourneert:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Een [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).