---
title: Cell
second_title: Aspose.Slides voor Java API-referentie
description: Representeert een cel van een tabel.
type: docs
url: /nl/com.aspose.slides/cell/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Stelt een cel van een tabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Retourneert een afstand van de linkerkant van een tabel tot de linkerkant van een cel. |
| [getOffsetY()](#getOffsetY--) | Retourneert een afstand van de bovenkant van een tabel tot de bovenkant van een cel. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Retourneert de index van de eerste rij die door de cel wordt bedekt. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Retourneert de index van de eerste kolom die door de cel wordt bedekt. |
| [getWidth()](#getWidth--) | Retourneert de breedte van de cel. |
| [getHeight()](#getHeight--) | Retourneert de hoogte van de cel. |
| [getMinimalHeight()](#getMinimalHeight--) | Retourneert de minimale hoogte van een cel. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert of stelt de linkermarge in een TextFrame in. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Retourneert of stelt de linkermarge in een TextFrame in. |
| [getMarginRight()](#getMarginRight--) | Retourneert of stelt de rechtermarge in een TextFrame in. |
| [setMarginRight(double value)](#setMarginRight-double-) | Retourneert of stelt de rechtermarge in een TextFrame in. |
| [getMarginTop()](#getMarginTop--) | Retourneert of stelt de bovengrens in een TextFrame in. |
| [setMarginTop(double value)](#setMarginTop-double-) | Retourneert of stelt de bovengrens in een TextFrame in. |
| [getMarginBottom()](#getMarginBottom--) | Retourneert of stelt de onderrand in een TextFrame in. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Retourneert of stelt de onderrand in een TextFrame in. |
| [getTextVerticalType()](#getTextVerticalType--) | Retourneert of stelt het type verticale tekst in. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Retourneert of stelt het type verticale tekst in. |
| [getTextAnchorType()](#getTextAnchorType--) | Retourneert of stelt het anker-type van de tekst in. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Retourneert of stelt het anker-type van de tekst in. |
| [getAnchorCenter()](#getAnchorCenter--) | Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. |
| [getFirstRow()](#getFirstRow--) | Haalt de eerste rij van de cel op. |
| [getFirstColumn()](#getFirstColumn--) | Haalt de eerste kolom van de cel op. |
| [getColSpan()](#getColSpan--) | Retourneert het aantal raster-kolommen in het tabelraster van de bovenliggende tabel die door de huidige cel worden overspannen. |
| [getRowSpan()](#getRowSpan--) | Retourneert het aantal rijen dat een samengevoegde cel beslaat. |
| [getTextFrame()](#getTextFrame--) | Retourneert het tekstkader van een cel. |
| [getTable()](#getTable--) | Retourneert het bovenliggende Table-object voor een cel. |
| [isMergedCell()](#isMergedCell--) | Retourneert true als de cel is samengevoegd met een aangepaste cel, anders false. |
| [getCellFormat()](#getCellFormat--) | Retourneert het CellFormat-object dat de opmaak-eigenschappen voor deze cel bevat. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Splitst de cel in twee cellen op basis van de kolomindex. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Splitst de cel in twee cellen op basis van de rij-index. |
| [splitByHeight(double height)](#splitByHeight-double-) | Splitst de cel op basis van hoogte. |
| [splitByWidth(double width)](#splitByWidth-double-) | Splitst de cel op basis van breedte. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een cel. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een cel. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Retourneert een afstand van de linkerkant van een tabel tot de linkerkant van een cel. Alleen-lezen double.

**Retourneert:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Retourneert een afstand van de bovenkant van een tabel tot de bovenkant van een cel. Alleen-lezen double.

**Retourneert:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Retourneert de index van de eerste rij die door de cel wordt bedekt. Alleen-lezen int.

**Retourneert:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Retourneert de index van de eerste kolom die door de cel wordt bedekt. Alleen-lezen int.

**Retourneert:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Retourneert de breedte van de cel. Alleen-lezen double.

**Retourneert:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Retourneert de hoogte van de cel. Alleen-lezen double.

**Retourneert:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Retourneert de minimale hoogte van een cel. Dit is de som van de minimale hoogtes van alle rijen die door de cel worden gedekt. Alleen-lezen double.

**Retourneert:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Retourneert of stelt de linkermarge in een TextFrame in. Lezen/Schrijven double.

**Retourneert:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Retourneert of stelt de linkermarge in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Retourneert of stelt de rechtermarge in een TextFrame in. Lezen/Schrijven double.

**Retourneert:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Retourneert of stelt de rechtermarge in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Retourneert of stelt de bovengrens in een TextFrame in. Lezen/Schrijven double.

**Retourneert:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Retourneert of stelt de bovengrens in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Retourneert of stelt de onderrand in een TextFrame in. Lezen/Schrijven double.

**Retourneert:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Retourneert of stelt de onderrand in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Retourneert of stelt het type verticale tekst in. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retourneert:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Retourneert of stelt het type verticale tekst in. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Retourneert of stelt het anker-type van de tekst in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retourneert:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Retourneert of stelt het anker-type van de tekst in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Bepaalt of het tekstvak al dan niet gecentreerd is binnen een cel. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Haalt de eerste rij van de cel op. Alleen-lezen [IRow](../../com.aspose.slides/irow).

**Retourneert:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Haalt de eerste kolom van de cel op. Alleen-lezen [IColumn](../../com.aspose.slides/icolumn).

**Retourneert:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Retourneert het aantal raster-kolommen in het tabelraster van de bovenliggende tabel die door de huidige cel worden overspannen. Deze eigenschap maakt het mogelijk dat cellen de indruk wekken samengevoegd te zijn, omdat ze verticale grenzen van andere cellen overspannen. Alleen-lezen int.

**Retourneert:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Retourneert het aantal rijen dat een samengevoegde cel beslaat. Dit wordt gebruikt in combinatie met het vMerge-attribuut op andere cellen om de begincel van een horizontale samenvoeging te specificeren. Alleen-lezen int.

**Retourneert:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Retourneert het tekstkader van een cel. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retourneert:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Retourneert het bovenliggende Table-object voor een cel. Alleen-lezen [ITable](../../com.aspose.slides/itable).

**Retourneert:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Retourneert true als de cel is samengevoegd met een aangepaste cel, anders false. Alleen-lezen boolean.

**Retourneert:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Retourneert het CellFormat-object dat de opmaak-eigenschappen voor deze cel bevat. Alleen-lezen [ICellFormat](../../com.aspose.slides/icellformat).

**Retourneert:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Splitst de cel in twee cellen op basis van de kolomindex.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van kolom. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Splitst de cel in twee cellen op basis van de rij-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van rij. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Splitst de cel op basis van hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| height | double | Hoogte van een rij. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Splitst de cel op basis van breedte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | double | Breedte van een kolom. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een cel. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een cel. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject