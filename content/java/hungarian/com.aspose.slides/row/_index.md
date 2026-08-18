---
title: Row
second_title: Aspose.Slides Java API Referencia
description: A táblázat egy sorát reprezentálja.
type: docs
url: /hu/com.aspose.slides/row/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Összes megvalósított interfész:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Egy táblázat sorát reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeight()](#getHeight--) | Visszaadja egy sor magasságát. |
| [getMinimalHeight()](#getMinimalHeight--) | Visszaadja vagy beállítja egy sor minimális lehetséges magasságát. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Visszaadja vagy beállítja egy sor minimális lehetséges magasságát. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Beállítja a meghatározott részformátum tulajdonságait az összes sorcellához tartozó részekre. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Beállítja a meghatározott bekezdésformátum tulajdonságait az összes sorcellához tartozó bekezdésekre. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Beállítja a meghatározott szövegkeret formátum tulajdonságait az összes sorcellához tartozó szövegkeretekre. |
| [getRowFormat()](#getRowFormat--) | Visszaadja a RowFormat objektumot, amely a sor formázási tulajdonságait tartalmazza. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Visszaadja egy sor magasságát. Csak olvasható double.

**Visszatérési érték:**
double
### getMinimalHeight() {#getMinimalHeight--}
``` 
public final double getMinimalHeight()
```

Visszaadja vagy beállítja egy sor minimális lehetséges magasságát. Olvasható/írható double.

**Visszatérési érték:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Visszaadja vagy beállítja egy sor minimális lehetséges magasságát. Olvasható/írható double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Beállítja a meghatározott részformátum tulajdonságait az összes sorcellához tartozó részekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat objektum a szükséges tulajdonságok beállításával. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Beállítja a meghatározott bekezdésformátum tulajdonságait az összes sorcellához tartozó bekezdésekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat objektum a szükséges tulajdonságok beállításával. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Beállítja a meghatározott szövegkeret-formátum tulajdonságait az összes sorcellához tartozó szövegkeretekre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat objektum a szükséges tulajdonságok beállításával. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Visszaadja a RowFormat objektumot, amely a sor formázási tulajdonságait tartalmazza. Csak olvasható [IRowFormat](../../com.aspose.slides/irowformat).

**Visszatérési érték:**
[IRowFormat](../../com.aspose.slides/irowformat)