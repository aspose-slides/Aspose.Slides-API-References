---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Represents format of a table.
type: docs
url: /nl/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Geeft het formaat van een tabel weer.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retourneert een tabelvullingsobject. |
| [getTransparency()](#getTransparency--) | Haalt of stelt de transparantie van de vulkleur in. |
| [setTransparency(float value)](#setTransparency-float-) | Haalt of stelt de transparantie van de vulkleur in. |
| [getEffective()](#getEffective--) | Haalt effectieve tabelopmaak eigenschappen op met overerving en toegepaste tabelstijlen. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Retourneert een tabelvullingsobject. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Haalt of stelt de transparantie van de vulkleur in. Lezen/schrijven  float .

**Retour:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Haalt of stelt de transparantie van de vulkleur in. Lezen/schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Haalt effectieve tabelopmaak eigenschappen op met overerving en toegepaste tabelstijlen.

**Retour:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Een [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).