---
title: Column
second_title: Aspose.Slides Androidra a Java API hivatkozás segítségével
description: Egy táblázat oszlopát képviseli.
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

Egy táblázat oszlopát képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getWidth()](#getWidth--) | Visszaadja vagy beállítja egy oszlop szélességét. |
| [setWidth(double value)](#setWidth-double-) | Visszaadja vagy beállítja egy oszlop szélességét. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Beállítja a meghatározott részformázási tulajdonságokat az összes oszlopcellában lévő részekre. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Beállítja a meghatározott bekezdésformázási tulajdonságokat az összes oszlopcellában lévő bekezdésekre. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Beállítja a meghatározott szövegkeret-formázási tulajdonságokat az összes oszlopcellában lévő szövegkeretekre. |
| [getColumnFormat()](#getColumnFormat--) | Visszaadja a ColumnFormat objektumot, amely tartalmazza ennek az oszlopnak a formázási tulajdonságait. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Visszaadja vagy beállítja egy oszlop szélességét. Olvasható/írható double.

**Visszatér:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Visszaadja vagy beállítja egy oszlop szélességét. Olvasható/írható double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Beállítja a meghatározott részformázási tulajdonságokat az összes oszlopcellában lévő részekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat objektum a szükséges beállított tulajdonságokkal. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Beállítja a meghatározott bekezdésformázási tulajdonságokat az összes oszlopcellában lévő bekezdésekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat objektum a szükséges beállított tulajdonságokkal. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Beállítja a meghatározott szövegkeret-formázási tulajdonságokat az összes oszlopcellában lévő szövegkeretekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat objektum a szükséges beállított tulajdonságokkal. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Visszaadja a ColumnFormat objektumot, amely tartalmazza ennek az oszlopnak a formázási tulajdonságait. Csak olvasható [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Visszatér:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)