---
title: IColumn
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een kolom in een tabel voor.
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
| [getWidth()](#getWidth--) | Geeft de breedte van een kolom terug of stelt deze in. |
| [setWidth(double value)](#setWidth-double-) | Geeft de breedte van een kolom terug of stelt deze in. |
| [getColumnFormat()](#getColumnFormat--) | Geeft het ColumnFormat-object terug dat opmaak-eigenschappen voor deze kolom bevat. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Geeft de breedte van een kolom terug of stelt deze in. Lezen/schrijven double.

**Retour:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Geeft de breedte van een kolom terug of stelt deze in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Geeft het ColumnFormat-object terug dat opmaak-eigenschappen voor deze kolom bevat. Alleen-lezen [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Retour:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)