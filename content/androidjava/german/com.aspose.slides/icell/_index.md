---
title: ICell
second_title: Aspose.Slides für Android via Java API Referenz
description: Stellt eine Zelle in einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/icell/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Stellt eine Zelle in einer Tabelle dar.
## Methoden

| Method | Description |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Gibt einen Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. |
| [getOffsetY()](#getOffsetY--) | Gibt einen Abstand von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Gibt den Index der ersten von der Zelle abgedeckten Zeile zurück. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Gibt den Index der ersten von der Zelle abgedeckten Spalte zurück. |
| [getWidth()](#getWidth--) | Gibt die Breite der Zelle zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe der Zelle zurück. |
| [getMinimalHeight()](#getMinimalHeight--) | Gibt die minimale Höhe einer Zelle zurück. |
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand in einem TextFrame zurück oder legt ihn fest. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Gibt den linken Rand in einem TextFrame zurück oder legt ihn fest. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand in einem TextFrame zurück oder legt ihn fest. |
| [setMarginRight(double value)](#setMarginRight-double-) | Gibt den rechten Rand in einem TextFrame zurück oder legt ihn fest. |
| [getMarginTop()](#getMarginTop--) | Gibt den oberen Rand in einem TextFrame zurück oder legt ihn fest. |
| [setMarginTop(double value)](#setMarginTop-double-) | Gibt den oberen Rand in einem TextFrame zurück oder legt ihn fest. |
| [getMarginBottom()](#getMarginBottom--) | Gibt den unteren Rand in einem TextFrame zurück oder legt ihn fest. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Gibt den unteren Rand in einem TextFrame zurück oder legt ihn fest. |
| [getTextVerticalType()](#getTextVerticalType--) | Gibt den Typ des vertikalen Textes zurück oder legt ihn fest. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Gibt den Typ des vertikalen Textes zurück oder legt ihn fest. |
| [getTextAnchorType()](#getTextAnchorType--) | Gibt den Textanker-Typ zurück oder legt ihn fest. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Gibt den Textanker-Typ zurück oder legt ihn fest. |
| [getAnchorCenter()](#getAnchorCenter--) | Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. |
| [getFirstColumn()](#getFirstColumn--) | Holt die erste Spalte der Zelle. |
| [getFirstRow()](#getFirstRow--) | Holt die erste Zeile der Zelle. |
| [getColSpan()](#getColSpan--) | Gibt die Anzahl der Rasterspalten im Tabellenraster der übergeordneten Tabelle zurück, die von der aktuellen Zelle überschritten werden sollen. |
| [getRowSpan()](#getRowSpan--) | Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überspannt. |
| [getTextFrame()](#getTextFrame--) | Gibt den TextFrame einer Zelle zurück. |
| [getTable()](#getTable--) | Gibt das übergeordnete Table-Objekt einer Zelle zurück. |
| [isMergedCell()](#isMergedCell--) | Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, ansonsten false. |
| [getCellFormat()](#getCellFormat--) | Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Teilt die Zelle anhand des Spaltenindex in zwei Zellen. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Teilt die Zelle anhand des Zeilenindex in zwei Zellen. |
| [splitByHeight(double height)](#splitByHeight-double-) | Teilt die Zelle nach Höhe. |
| [splitByWidth(double width)](#splitByWidth-double-) | Teilt die Zelle nach Breite. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```


Gibt einen Abstand von der linken Seite einer Tabelle zur linken Seite einer Zelle zurück. **Nur lesbar** double.

**Rückgabe:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```


Gibt einen Abstand von der oberen Seite einer Tabelle zur oberen Seite einer Zelle zurück. **Nur lesbar** double.

**Rückgabe:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```


Gibt den Index der ersten von der Zelle abgedeckten Zeile zurück. **Nur lesbar** int.

**Rückgabe:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```


Gibt den Index der ersten von der Zelle abgedeckten Spalte zurück. **Nur lesbar** int.

**Rückgabe:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Gibt die Breite der Zelle zurück. **Nur lesbar** double.

**Rückgabe:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Gibt die Höhe der Zelle zurück. **Nur lesbar** double.

**Rückgabe:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Gibt die minimale Höhe einer Zelle zurück. Dies ist die Summe der minimalen Höhen aller von der Zelle abgedeckten Zeilen. **Nur lesbar** double.

**Rückgabe:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Gibt den linken Rand in einem TextFrame zurück oder legt ihn fest. **Lesen/Schreiben** double.

**Rückgabe:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Gibt den linken Rand in einem TextFrame zurück oder legt ihn fest. **Lesen/Schreiben** double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Gibt den rechten Rand in einem TextFrame zurück oder legt ihn fest. **Lesen/Schreiben** double.

**Rückgabe:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Gibt den rechten Rand in einem TextFrame zurück oder legt ihn fest. **Lesen/Schreiben** double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Gibt den oberen Rand in einem TextFrame zurück oder legt ihn fest. **Lesen/Schreiben** double.

**Rückgabe:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Gibt den oberen Rand in einem TextFrame zurück oder legt ihn fest. **Lesen/Schreiben** double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Gibt den unteren Rand in einem TextFrame zurück oder legt ihn fest. **Lesen/Schreiben** double.

**Rückgabe:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Gibt den unteren Rand in einem TextFrame zurück oder legt ihn fest. **Lesen/Schreiben** double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Gibt den Typ des vertikalen Textes zurück oder legt ihn fest. **Lesen/Schreiben** [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Rückgabe:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Gibt den Typ des vertikalen Textes zurück oder legt ihn fest. **Lesen/Schreiben** [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```


Gibt den Textanker-Typ zurück oder legt ihn fest. **Lesen/Schreiben** [TextAnchorType](../../com.aspose.slides/textanchortype).

**Rückgabe:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```


Gibt den Textanker-Typ zurück oder legt ihn fest. **Lesen/Schreiben** [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```


Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. **Lesen/Schreiben** boolean.

**Rückgabe:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```


Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht. **Lesen/Schreiben** boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```


Holt die erste Spalte der Zelle. **Nur lesbar** [IColumn](../../com.aspose.slides/icolumn).

**Rückgabe:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```


Holt die erste Zeile der Zelle. **Nur lesbar** [IRow](../../com.aspose.slides/irow).

**Rückgabe:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```


Gibt die Anzahl der Rasterspalten im Tabellenraster der übergeordneten Tabelle zurück, die von der aktuellen Zelle überschritten werden sollen. Diese Eigenschaft ermöglicht das Aussehen zusammengeführter Zellen, da sie vertikale Grenzen anderer Zellen in der Tabelle überspannen. **Nur lesbar** int.

**Rückgabe:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```


Gibt die Anzahl der Zeilen zurück, die eine zusammengeführte Zelle überspannt. Dies wird in Kombination mit dem vMerge-Attribut anderer Zellen verwendet, um die Ausgangszelle einer horizontalen Zusammenführung zu bestimmen. **Nur lesbar** int.

**Rückgabe:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Gibt den TextFrame einer Zelle zurück. **Nur lesbar** [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```


Gibt das übergeordnete Table-Objekt einer Zelle zurück. **Nur lesbar** [ITable](../../com.aspose.slides/itable).

**Rückgabe:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```


Gibt true zurück, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, ansonsten false. **Nur lesbar** boolean.

**Rückgabe:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```


Gibt das CellFormat-Objekt zurück, das Formatierungseigenschaften für diese Zelle enthält. **Nur lesbar** [ICellFormat](../../com.aspose.slides/icellformat).

**Rückgabe:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```


Teilt die Zelle anhand des Spaltenindex in zwei Zellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der Spalte. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```


Teilt die Zelle anhand des Zeilenindex in zwei Zellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der Zeile. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```


Teilt die Zelle nach Höhe.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| height | double | Höhe einer Zeile. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```


Teilt die Zelle nach Breite.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | double | Breite einer Spalte. |