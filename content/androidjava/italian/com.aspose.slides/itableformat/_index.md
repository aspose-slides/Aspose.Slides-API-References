---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table.
type: docs
url: /it/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Rappresenta il formato di una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Restituisce un oggetto di proprietà di riempimento della tabella. |
| [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza del colore di riempimento. |
| [setTransparency(float value)](#setTransparency-float-) | Ottiene o imposta la trasparenza del colore di riempimento. |
| [getEffective()](#getEffective--) | Ottiene le proprietà di formattazione della tabella effettive con ereditarietà e stili di tabella applicati. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Restituisce un oggetto di proprietà di riempimento della tabella. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Ottiene o imposta la trasparenza del colore di riempimento. Lettura/scrittura  float .

**Restituisce:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Ottiene o imposta la trasparenza del colore di riempimento. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Ottiene le proprietà di formattazione della tabella effettive con ereditarietà e stili di tabella applicati.

**Restituisce:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Un [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).