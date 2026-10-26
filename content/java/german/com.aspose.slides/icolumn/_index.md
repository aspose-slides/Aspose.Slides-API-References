---
title: IColumn
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Spalte in einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/icolumn/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Stellt eine Spalte in einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Gibt die Breite einer Spalte zurück oder legt sie fest. |
| [setWidth(double value)](#setWidth-double-) | Gibt die Breite einer Spalte zurück oder legt sie fest. |
| [getColumnFormat()](#getColumnFormat--) | Gibt das ColumnFormat-Objekt zurück, das Formatierungseigenschaften für diese Spalte enthält. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Gibt die Breite einer Spalte zurück oder legt sie fest. Lesen/Schreiben double.

**Rückgabe:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Gibt die Breite einer Spalte zurück oder legt sie fest. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Gibt das ColumnFormat-Objekt zurück, das Formatierungseigenschaften für diese Spalte enthält. Nur-lesen [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Rückgabe:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)