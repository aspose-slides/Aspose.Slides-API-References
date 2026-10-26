---
title: IColumn
second_title: Aspose.Slides voor Android via Java API Referentie
description: Representeert een kolom in een tabel.
type: docs
url: /nl/com.aspose.slides/icolumn/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Stelt een kolom in een tabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Retourneert of stelt de breedte van een kolom in. |
| [setWidth(double value)](#setWidth-double-) | Retourneert of stelt de breedte van een kolom in. |
| [getColumnFormat()](#getColumnFormat--) | Retourneert het ColumnFormat-object dat opmaak eigenschappen voor deze kolom bevat. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Retourneert of stelt de breedte van een kolom in. Lezen/Schrijven double.

**Retour:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Retourneert of stelt de breedte van een kolom in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Retourneert het ColumnFormat-object dat opmaak eigenschappen voor deze kolom bevat. Alleen-lezen [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Retour:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)