---
title: Column
second_title: Aspose.Slides für Java API Referenz
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
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Setzt definierte Portion-Format-Eigenschaften für alle Portionen der Spaltenzellen. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Setzt definierte Absatzformat-Eigenschaften für alle Absätze der Spaltenzellen. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Setzt definierte Textfeldformat-Eigenschaften für alle Textrahmen der Spaltenzellen. |
| [getColumnFormat()](#getColumnFormat--) | Gibt das ColumnFormat-Objekt zurück, das die Formatierungseigenschaften für diese Spalte enthält. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Gibt die Breite einer Spalte zurück oder setzt sie. Lesen/Schreiben double.

**Rückgabe:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Gibt die Breite einer Spalte zurück oder setzt sie. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Setzt definierte Portion-Format-Eigenschaften für alle Portionen der Spaltenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Setzt definierte Absatzformat-Eigenschaften für alle Absätze der Spaltenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

Setzt definierte Textfeldformat-Eigenschaften für alle Textrahmen der Spaltenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Gibt das ColumnFormat-Objekt zurück, das die Formatierungseigenschaften für diese Spalte enthält. Nur lesend [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Rückgabe:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)