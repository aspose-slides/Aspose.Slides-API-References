---
title: ICell
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een cel in een tabel voor.
type: docs
url: /nl/com.aspose.slides/icell/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Stelt een cel in een tabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Retourneert een afstand van de linkerkant van een tabel tot de linkerkant van een cel. |
| [getOffsetY()](#getOffsetY--) | Retourneert een afstand van de bovenkant van een tabel tot de bovenkant van een cel. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Retourneert de index van de eerste rij die door de cel wordt gedekt. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Retourneert de index van de eerste kolom die door de cel wordt gedekt. |
| [getWidth()](#getWidth--) | Retourneert de breedte van de cel. |
| [getHeight()](#getHeight--) | Retourneert de hoogte van de cel. |
| [getMinimalHeight()](#getMinimalHeight--) | Retourneert de minimale hoogte van een cel. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert of stelt de linkermarge in een TextFrame in. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Retourneert of stelt de linkermarge in een TextFrame in. |
| [getMarginRight()](#getMarginRight--) | Retourneert of stelt de rechtermarge in een TextFrame in. |
| [setMarginRight(double value)](#setMarginRight-double-) | Retourneert of stelt de rechtermarge in een TextFrame in. |
| [getMarginTop()](#getMarginTop--) | Retourneert of stelt de bovenmarge in een TextFrame in. |
| [setMarginTop(double value)](#setMarginTop-double-) | Retourneert of stelt de bovenmarge in een TextFrame in. |
| [getMarginBottom()](#getMarginBottom--) | Retourneert of stelt de ondermarge in een TextFrame in. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Retourneert of stelt de ondermarge in een TextFrame in. |
| [getTextVerticalType()](#getTextVerticalType--) | Retourneert of stelt het type verticale tekst in. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Retourneert of stelt het type verticale tekst in. |
| [getTextAnchorType()](#getTextAnchorType--) | Retourneert of stelt het anker type van de tekst in. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Retourneert of stelt het anker type van de tekst in. |
| [getAnchorCenter()](#getAnchorCenter--) | Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. |
| [getFirstColumn()](#getFirstColumn--) | Haal de eerste kolom van de cel op. |
| [getFirstRow()](#getFirstRow--) | Haal de eerste rij van de cel op. |
| [getColSpan()](#getColSpan--) | Retourneert het aantal rasterkolommen in het tabelraster van de bovenliggende tabel dat door de huidige cel moet worden overspannen. |
| [getRowSpan()](#getRowSpan--) | Retourneert het aantal rijen dat een samengevoegde cel overspant. |
| [getTextFrame()](#getTextFrame--) | Retourneert het tekstframe van een cel. |
| [getTable()](#getTable--) | Retourneert het bovenliggende Table-object voor een cel. |
| [isMergedCell()](#isMergedCell--) | Retourneert true als de cel is samengevoegd met een aangepaste cel, anders false. |
| [getCellFormat()](#getCellFormat--) | Retourneert het CellFormat-object dat de opmaak-eigenschappen voor deze cel bevat. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Splitst de cel in twee cellen op basis van kolomindex. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Splitst de cel in twee cellen op basis van rijindex. |
| [splitByHeight(double height)](#splitByHeight-double-) | Splitst de cel op basis van hoogte. |
| [splitByWidth(double width)](#splitByWidth-double-) | Splitst de cel op basis van breedte. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Retourneert een afstand van de linkerkant van een tabel tot de linkerkant van een cel. Alleen-lezen double.

**Retour:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Retourneert een afstand van de bovenkant van een tabel tot de bovenkant van een cel. Alleen-lezen double.

**Retour:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Retourneert de index van de eerste rij die door de cel wordt gedekt. Alleen-lezen int.

**Retour:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Retourneert de index van de eerste kolom die door de cel wordt gedekt. Alleen-lezen int.

**Retour:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Retourneert de breedte van de cel. Alleen-lezen double.

**Retour:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Retourneert de hoogte van de cel. Alleen-lezen double.

**Retour:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Retourneert de minimale hoogte van een cel. Dit is de som van de minimale hoogtes van alle rijen die door de cel worden gedekt. Alleen-lezen double.

**Retour:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Retourneert of stelt de linkermarge in een TextFrame in. Lezen/Schrijven double.

**Retour:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Retourneert of stelt de linkermarge in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Retourneert of stelt de rechtermarge in een TextFrame in. Lezen/Schrijven double.

**Retour:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Retourneert of stelt de rechtermarge in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Retourneert of stelt de bovenmarge in een TextFrame in. Lezen/Schrijven double.

**Retour:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Retourneert of stelt de bovenmarge in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Retourneert of stelt de ondermarge in een TextFrame in. Lezen/Schrijven double.

**Retour:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Retourneert of stelt de ondermarge in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Retourneert of stelt het type verticale tekst in. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retour:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Retourneert of stelt het type verticale tekst in. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Retourneert of stelt het anker type van de tekst in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retour:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Retourneert of stelt het anker type van de tekst in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. Lezen/Schrijven boolean.

**Retour:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Haal de eerste kolom van de cel op. Alleen-lezen [IColumn](../../com.aspose.slides/icolumn).

**Retour:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Haal de eerste rij van de cel op. Alleen-lezen [IRow](../../com.aspose.slides/irow).

**Retour:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Retourneert het aantal rasterkolommen in het tabelraster van de bovenliggende tabel dat door de huidige cel moet worden overspannen. Deze eigenschap maakt het mogelijk dat cellen de indruk wekken samengevoegd te zijn, doordat ze verticale grenzen van andere cellen in de tabel overspannen. Alleen-lezen int.

**Retour:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Retourneert het aantal rijen dat een samengevoegde cel overspant. Dit wordt gebruikt in combinatie met het vMerge-attribuut op andere cellen om de begincel van een horizontale samenvoeging te specificeren. Alleen-lezen int.

**Retour:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Retourneert het tekstframe van een cel. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Retourneert het bovenliggende Table-object voor een cel. Alleen-lezen [ITable](../../com.aspose.slides/itable).

**Retour:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Retourneert true als de cel is samengevoegd met een aangepaste cel, anders false. Alleen-lezen boolean.

**Retour:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Retourneert het CellFormat-object dat de opmaak-eigenschappen voor deze cel bevat. Alleen-lezen [ICellFormat](../../com.aspose.slides/icellformat).

**Retour:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Splitst de cel in twee cellen op basis van kolomindex.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van kolom. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Splitst de cel in twee cellen op basis van rijindex.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van rij. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Splitst de cel op basis van hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| height | double | Hoogte van een rij. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Splitst de cel op basis van breedte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | double | Breedte van een kolom. |