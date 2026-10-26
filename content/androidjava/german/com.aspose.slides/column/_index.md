---
title: Column
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Spalte in einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/column/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Stellt eine Spalte in einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Gibt die Breite einer Spalte zurück oder setzt sie. |
| [setWidth(double value)](#setWidth-double-) | Gibt die Breite einer Spalte zurück oder setzt sie. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Setzt die definierten Portionformat-Eigenschaften für alle Spaltenzellen-Portionen. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Setzt die definierten Absatzformat-Eigenschaften für alle Spaltenzellen-Absätze. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Setzt die definierten Textrahmenformat-Eigenschaften für alle Spaltenzellen-Textrahmen. |
| [getColumnFormat()](#getColumnFormat--) | Gibt das ColumnFormat Objekt zurück, das Formatierungseigenschaften für diese Spalte enthält. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Gibt die Breite einer Spalte zurück oder setzt sie. Lese/Schreib double.

**Rückgabe:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Gibt die Breite einer Spalte zurück oder setzt sie. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Setzt die definierten Portionformat-Eigenschaften für alle Spaltenzellen-Portionen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat Objekt mit den erforderlichen Eigenschaften gesetzt. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Setzt die definierten Absatzformat-Eigenschaften für alle Spaltenzellen-Absätze.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat Objekt mit den erforderlichen Eigenschaften gesetzt. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Setzt die definierten Textrahmenformat-Eigenschaften für alle Spaltenzellen-Textrahmen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat Objekt mit den erforderlichen Eigenschaften gesetzt. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Gibt das ColumnFormat Objekt zurück, das Formatierungseigenschaften für diese Spalte enthält. Nur-lesen [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Rückgabe:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)