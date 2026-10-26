---
title: Column
second_title: Aspose.Slides a Java API referenciája
description: Egy táblázat oszlopát reprezentálja.
type: docs
url: /hu/com.aspose.slides/column/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Minden megvalósított interfész:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

A táblázat egy oszlopát képviseli.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getWidth()](#getWidth--) | Visszaadja vagy beállítja egy oszlop szélességét. |
| [setWidth(double value)](#setWidth-double-) | Visszaadja vagy beállítja egy oszlop szélességét. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Beállítja a meghatározott részletformátum tulajdonságokat az összes oszlopcellához tartozó részekre. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Beállítja a meghatározott bekezdésformátum tulajdonságokat az összes oszlopcellához tartozó bekezdésekre. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Beállítja a meghatározott szövegkeret-formátum tulajdonságokat az összes oszlopcellához tartozó szövegkeretekre. |
| [getColumnFormat()](#getColumnFormat--) | Visszaadja a ColumnFormat objektumot, amely ezt az oszlopot formázó tulajdonságokat tartalmazza. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Visszaadja vagy beállítja egy oszlop szélességét. Olvasás/írás double.

**Visszatér:**  
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Visszaadja vagy beállítja egy oszlop szélességét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Beállítja a meghatározott részletformátum tulajdonságokat az összes oszlopcellához tartozó részekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Beállítja a meghatározott bekezdésformátum tulajdonságokat az összes oszlopcellához tartozó bekezdésekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) |  |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Beállítja a meghatározott szövegkeret-formátum tulajdonságokat az összes oszlopcellához tartozó szövegkeretekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) |  |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Visszaadja a ColumnFormat objektumot, amely ezt az oszlopot formázó tulajdonságokat tartalmazza. Csak olvasható [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Visszatér:**  
[IColumnFormat](../../com.aspose.slides/icolumnformat)