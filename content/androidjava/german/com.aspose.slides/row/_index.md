---
title: Row
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Zeile in einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/row/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Stellt eine Zeile in einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeight()](#getHeight--) | Gibt die Höhe einer Zeile zurück. |
| [getMinimalHeight()](#getMinimalHeight--) | Gibt die minimale mögliche Höhe einer Zeile zurück oder legt sie fest. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Gibt die minimale mögliche Höhe einer Zeile zurück oder legt sie fest. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Setzt definierte Portion-Format-Eigenschaften für alle Zellenportionen der Zeile. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Setzt definierte Absatzformat-Eigenschaften für alle Zeilenzellenabsätze. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Setzt definierte Textfeld-Format-Eigenschaften für alle Textrahmen der Zeilenzellen. |
| [getRowFormat()](#getRowFormat--) | Gibt das RowFormat-Objekt zurück, das Formatierungseigenschaften für diese Zeile enthält. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Gibt die Höhe einer Zeile zurück. Nur lesbar double.

**Rückgabe:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Gibt die minimale mögliche Höhe einer Zeile zurück oder legt sie fest. Lese-/Schreibzugriff double.

**Rückgabe:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Gibt die minimale mögliche Höhe einer Zeile zurück oder legt sie fest. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Setzt definierte Portion-Format-Eigenschaften für alle Portionen der Zeilenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-Objekt mit den erforderlichen Eigenschaften gesetzt. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Setzt definierte Absatzformat-Eigenschaften für alle Absätze der Zeilenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-Objekt mit den erforderlichen Eigenschaften gesetzt. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Setzt definierte Textfeld-Format-Eigenschaften für alle Textrahmen der Zeilenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-Objekt mit den erforderlichen Eigenschaften gesetzt. |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Gibt das RowFormat-Objekt zurück, das Formatierungseigenschaften für diese Zeile enthält. Nur lesbar [IRowFormat](../../com.aspose.slides/irowformat).

**Rückgabe:**
[IRowFormat](../../com.aspose.slides/irowformat)