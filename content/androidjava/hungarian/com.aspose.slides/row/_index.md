---
title: Row
second_title: Aspose.Slides Androidra vonatkozó Java API-referencia
description: Egy sort képvisel egy táblázatban.
type: docs
url: /hu/com.aspose.slides/row/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Az összes megvalósított interfész:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Egy sort képvisel egy táblázatban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeight()](#getHeight--) | Visszaadja a sor magasságát. |
| [getMinimalHeight()](#getMinimalHeight--) | Visszaadja vagy beállítja a sor minimális lehetséges magasságát. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Visszaadja vagy beállítja a sor minimális lehetséges magasságát. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Beállítja a meghatározott részformátum tulajdonságait az összes sorcellához tartozó részekre. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Beállítja a meghatározott bekezdésformátum tulajdonságait az összes sorcellához tartozó bekezdésekre. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Beállítja a meghatározott szövegdoboz-formátum tulajdonságait az összes sorcellához tartozó szövegdobozokra. |
| [getRowFormat()](#getRowFormat--) | Visszaadja a RowFormat objektumot, amely formázási tulajdonságokat tartalmaz ehhez a sorhoz. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Visszaadja a sor magasságát. Csak olvasható double.

**Visszatér:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Visszaadja vagy beállítja a sor minimális lehetséges magasságát. Olvasható/írható double.

**Visszatér:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Visszaadja vagy beállítja a sor minimális lehetséges magasságát. Olvasható/írható double.

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

Beállítja a meghatározott szövegdoboz-formátum tulajdonságait az összes sorcellához tartozó szövegdobozokra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat objektum a szükséges tulajdonságok beállításával. |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Visszaadja a RowFormat objektumot, amely formázási tulajdonságokat tartalmaz ehhez a sorhoz. Csak olvasható [IRowFormat](../../com.aspose.slides/irowformat).

**Visszatér:**
[IRowFormat](../../com.aspose.slides/irowformat)