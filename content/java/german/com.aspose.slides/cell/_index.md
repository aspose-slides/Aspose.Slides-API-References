---
title: Cell
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Zelle einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/cell/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Stellt eine Zelle einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Gibt die Entfernung von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. |
| [getOffsetY()](#getOffsetY--) | Gibt die Entfernung von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Gibt den Index der ersten von der Zelle abgedeckten Zeile zurück. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Gibt den Index der ersten von der Zelle abgedeckten Spalte zurück. |
| [getWidth()](#getWidth--) | Gibt die Breite der Zelle zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe der Zelle zurück. |
| [getMinimalHeight()](#getMinimalHeight--) | Gibt die minimale Höhe einer Zelle zurück. |
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand in einem TextFrame zurück oder setzt ihn. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Gibt den linken Rand in einem TextFrame zurück oder setzt ihn. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand in einem TextFrame zurück oder setzt ihn. |
| [setMarginRight(double value)](#setMarginRight-double-) | Gibt den rechten Rand in einem TextFrame zurück oder setzt ihn. |
| [getMarginTop()](#getMarginTop--) | Gibt den oberen Rand in einem TextFrame zurück oder setzt ihn. |
| [setMarginTop(double value)](#setMarginTop-double-) | Gibt den oberen Rand in einem TextFrame zurück oder setzt ihn. |
| [getMarginBottom()](#getMarginBottom--) | Gibt den unteren Rand in einem TextFrame zurück oder setzt ihn. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Gibt den unteren Rand in einem TextFrame zurück oder setzt ihn. |
| [getTextVerticalType()](#getTextVerticalType--) | Gibt den Typ des vertikalen Textes zurück oder setzt ihn. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Gibt den Typ des vertikalen Textes zurück oder setzt ihn. |
| [getTextAnchorType()](#getTextAnchorType--) | Gibt den Textanker-Typ zurück oder setzt ihn. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Gibt den Textanker-Typ zurück oder setzt ihn. |
| [getAnchorCenter()](#getAnchorCenter--) | Bestimmt, ob das Textfeld innerhalb einer Zelle zentriert ist oder nicht. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Bestimmt, ob das Textfeld innerhalb einer Zelle zentriert ist oder nicht. |
| [getFirstRow()](#getFirstRow--) | Gibt die erste Zeile der Zelle zurück. |
| [getFirstColumn()](#getFirstColumn--) | Gibt die erste Spalte der Zelle zurück. |
| [getColSpan()](#getColSpan--) | Gibt die Anzahl der Rasterspalten im Tabellengitter der übergeordneten Tabelle zurück, die von der aktuellen Zelle überdeckt werden sollen. |
| [getRowSpan()](#getRowSpan--) | Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überspannt. |
| [getTextFrame()](#getTextFrame--) | Gibt den TextFrame einer Zelle zurück. |
| [getTable()](#getTable--) | Gibt das übergeordnete Table-Objekt einer Zelle zurück. |
| [isMergedCell()](#isMergedCell--) | Gibt true zurück, wenn die Zelle mit einer anderen angepassten Zelle zusammengeführt ist, sonst false. |
| [getCellFormat()](#getCellFormat--) | Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Teilt die Zelle anhand des Spaltenindex in zwei Zellen. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Teilt die Zelle anhand des Zeilenindex in zwei Zellen. |
| [splitByHeight(double height)](#splitByHeight-double-) | Teilt die Zelle nach Höhe. |
| [splitByWidth(double width)](#splitByWidth-double-) | Teilt die Zelle nach Breite. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie einer Zelle zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation einer Zelle zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Gibt die Entfernung von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. Nur-Lese double.

**Rückgabe:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Gibt die Entfernung von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. Nur-Lese double.

**Rückgabe:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Gibt den Index der ersten von der Zelle abgedeckten Zeile zurück. Nur-Lese int.

**Rückgabe:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Gibt den Index der ersten von der Zelle abgedeckten Spalte zurück. Nur-Lese int.

**Rückgabe:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Gibt die Breite der Zelle zurück. Nur-Lese double.

**Rückgabe:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Gibt die Höhe der Zelle zurück. Nur-Lese double.

**Rückgabe:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Gibt die minimale Höhe einer Zelle zurück. Dies ist die Summe der minimalen Höhen aller von der Zelle abgedeckten Zeilen. Nur-Lese double.

**Rückgabe:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Gibt den linken Rand in einem TextFrame zurück oder setzt ihn. Lese/Schreib double.

**Rückgabe:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Gibt den linken Rand in einem TextFrame zurück oder setzt ihn. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Gibt den rechten Rand in einem TextFrame zurück oder setzt ihn. Lese/Schreib double.

**Rückgabe:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Gibt den rechten Rand in einem TextFrame zurück oder setzt ihn. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Gibt den oberen Rand in einem TextFrame zurück oder setzt ihn. Lese/Schreib double.

**Rückgabe:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Gibt den oberen Rand in einem TextFrame zurück oder setzt ihn. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Gibt den unteren Rand in einem TextFrame zurück oder setzt ihn. Lese/Schreib double.

**Rückgabe:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Gibt den unteren Rand in einem TextFrame zurück oder setzt ihn. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Gibt den Typ des vertikalen Textes zurück oder setzt ihn. Lese/Schreib [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Rückgabe:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Gibt den Typ des vertikalen Textes zurück oder setzt ihn. Lese/Schreib [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Gibt den Textanker-Typ zurück oder setzt ihn. Lese/Schreib [TextAnchorType](../../com.aspose.slides/textanchortype).

**Rückgabe:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Gibt den Textanker-Typ zurück oder setzt ihn. Lese/Schreib [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Bestimmt, ob das Textfeld innerhalb einer Zelle zentriert ist oder nicht. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Bestimmt, ob das Textfeld innerhalb einer Zelle zentriert ist oder nicht. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Gibt die erste Zeile der Zelle zurück. Nur-Lese [IRow](../../com.aspose.slides/irow).

**Rückgabe:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Gibt die erste Spalte der Zelle zurück. Nur-Lese [IColumn](../../com.aspose.slides/icolumn).

**Rückgabe:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Gibt die Anzahl der Rasterspalten im Tabellengitter der übergeordneten Tabelle zurück, die von der aktuellen Zelle überdeckt werden sollen. Diese Eigenschaft ermöglicht es Zellen, den Anschein einer Zusammenführung zu haben, da sie vertikale Grenzen anderer Zellen in der Tabelle überspannen. Nur-Lese int.

**Rückgabe:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überspannt. Dies wird in Kombination mit dem vMerge-Attribut anderer Zellen verwendet, um die Beginnzelle einer horizontalen Zusammenführung anzugeben. Nur-Lese int.

**Rückgabe:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Gibt den TextFrame einer Zelle zurück. Nur-Lese [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Gibt das übergeordnete Table-Objekt einer Zelle zurück. Nur-Lese [ITable](../../com.aspose.slides/itable).

**Rückgabe:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Gibt true zurück, wenn die Zelle mit einer anderen angepassten Zelle zusammengeführt ist, sonst false. Nur-Lese boolean.

**Rückgabe:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. Nur-Lese [ICellFormat](../../com.aspose.slides/icellformat).

**Rückgabe:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Teilt die Zelle anhand des Spaltenindex in zwei Zellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der Spalte. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Teilt die Zelle anhand des Zeilenindex in zwei Zellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der Zeile. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Teilt die Zelle nach Höhe.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| height | double | Höhe einer Zeile. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Teilt die Zelle nach Breite.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | double | Breite einer Spalte. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie einer Zelle zurück. Nur-Lese [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation einer Zelle zurück. Nur-Lese [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt Parent_Immediate-Objekt zurück. Nur-Lese IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject