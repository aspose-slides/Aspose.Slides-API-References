---
title: IRow
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt eine Zeile in einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/irow/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Stellt eine Zeile in einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeight()](#getHeight--) | Gibt die Höhe einer Zeile zurück. |
| [getMinimalHeight()](#getMinimalHeight--) | Gibt die minimal mögliche Höhe einer Zeile zurück oder legt sie fest. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Gibt die minimal mögliche Höhe einer Zeile zurück oder legt sie fest. |
| [getRowFormat()](#getRowFormat--) | Gibt das RowFormat-Objekt zurück, das Formatierungseigenschaften für diese Zeile enthält. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Gibt die Höhe einer Zeile zurück. Nur lesbar double.

**Rückgabe:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Gibt die minimal mögliche Höhe einer Zeile zurück oder legt sie fest. Lese-/Schreib double.

**Rückgabe:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Gibt die minimal mögliche Höhe einer Zeile zurück oder legt sie fest. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Gibt das RowFormat-Objekt zurück, das Formatierungseigenschaften für diese Zeile enthält. Nur lesbar [IRowFormat](../../com.aspose.slides/irowformat).

**Rückgabe:**
[IRowFormat](../../com.aspose.slides/irowformat)