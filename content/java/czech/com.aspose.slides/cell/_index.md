---
title: Cell
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje buňku tabulky.
type: docs
url: /cs/com.aspose.slides/cell/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Representuje buňku tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Vrací vzdálenost z levé strany tabulky k levé straně buňky. |
| [getOffsetY()](#getOffsetY--) | Vrací vzdálenost z horní strany tabulky k horní straně buňky. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Vrací index prvního řádku, který buňka pokrývá. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Vrací index první sloupce, který buňka pokrývá. |
| [getWidth()](#getWidth--) | Vrací šířku buňky. |
| [getHeight()](#getHeight--) | Vrací výšku buňky. |
| [getMinimalHeight()](#getMinimalHeight--) | Vrací minimální výšku buňky. |
| [getMarginLeft()](#getMarginLeft--) | Vrací nebo nastavuje levý okraj v TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Vrací nebo nastavuje levý okraj v TextFrame. |
| [getMarginRight()](#getMarginRight--) | Vrací nebo nastavuje pravý okraj v TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Vrací nebo nastavuje pravý okraj v TextFrame. |
| [getMarginTop()](#getMarginTop--) | Vrací nebo nastavuje horní okraj v TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Vrací nebo nastavuje horní okraj v TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Vrací nebo nastavuje spodní okraj v TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Vrací nebo nastavuje spodní okraj v TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Vrací nebo nastavuje typ svislého textu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Vrací nebo nastavuje typ svislého textu. |
| [getTextAnchorType()](#getTextAnchorType--) | Vrací nebo nastavuje typ ukotvení textu. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Vrací nebo nastavuje typ ukotvení textu. |
| [getAnchorCenter()](#getAnchorCenter--) | Určuje, zda je textové pole uprostřed buňky. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Určuje, zda je textové pole uprostřed buňky. |
| [getFirstRow()](#getFirstRow--) | Získá první řádek buňky. |
| [getFirstColumn()](#getFirstColumn--) | Získá první sloupec buňky. |
| [getColSpan()](#getColSpan--) | Vrací počet sloupců v mřížce nadřazené tabulky, které má aktuální buňka zabrat. |
| [getRowSpan()](#getRowSpan--) | Vrací počet řádků, které sloučená buňka zabírá. |
| [getTextFrame()](#getTextFrame--) | Vrací textový rámec buňky. |
| [getTable()](#getTable--) | Vrací objekt rodičovské Tabulky pro buňku. |
| [isMergedCell()](#isMergedCell--) | Vrací true, pokud je buňka sloučena s jakoukoliv přizpůsobenou buňkou, jinak false. |
| [getCellFormat()](#getCellFormat--) | Vrací objekt CellFormat, který obsahuje formátovací vlastnosti pro tuto buňku. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Rozděluje buňku na dvě buňky podle indexu sloupce. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Rozděluje buňku na dvě buňky podle indexu řádku. |
| [splitByHeight(double height)](#splitByHeight-double-) | Rozděluje buňku podle výšky. |
| [splitByWidth(double width)](#splitByWidth-double-) | Rozděluje buňku podle šířky. |
| [getSlide()](#getSlide--) | Vrací rodičovský snímek buňky. |
| [getPresentation()](#getPresentation--) | Vrací rodičovskou prezentaci buňky. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```


Vrací vzdálenost z levé strany tabulky k levé straně buňky. Pouze ke čtení double.

**Vrací:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```


Vrací vzdálenost z horní strany tabulky k horní straně buňky. Pouze ke čtení double.

**Vrací:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```


Vrací index prvního řádku, který buňka pokrývá. Pouze ke čtení int.

**Vrací:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```


Vrací index první sloupce, který buňka pokrývá. Pouze ke čtení int.

**Vrací:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Vrací šířku buňky. Pouze ke čtení double.

**Vrací:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Vrací výšku buňky. Pouze ke čtení double.

**Vrací:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


Vrací minimální výšku buňky. Jedná se o součet minimálních výšek všech řádků, které buňka pokrývá. Pouze ke čtení double.

**Vrací:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


Vrací nebo nastavuje levý okraj v TextFrame. Čtení/zápis double.

**Vrací:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


Vrací nebo nastavuje levý okraj v TextFrame. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


Vrací nebo nastavuje pravý okraj v TextFrame. Čtení/zápis double.

**Vrací:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


Vrací nebo nastavuje pravý okraj v TextFrame. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


Vrací nebo nastavuje horní okraj v TextFrame. Čtení/zápis double.

**Vrací:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


Vrací nebo nastavuje horní okraj v TextFrame. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Vrací nebo nastavuje spodní okraj v TextFrame. Čtení/zápis double.

**Vrací:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


Vrací nebo nastavuje spodní okraj v TextFrame. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Vrací nebo nastavuje typ svislého textu. Čtení/zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Vrací nebo nastavuje typ svislého textu. Čtení/zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```


Vrací nebo nastavuje typ ukotvení textu. Čtení/zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```


Vrací nebo nastavuje typ ukotvení textu. Čtení/zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```


Určuje, zda je textové pole uprostřed buňky. Čtení/zápis boolean.

**Vrací:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```


Určuje, zda je textové pole uprostřed buňky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```


Získá první řádek buňky. Pouze ke čtení [IRow](../../com.aspose.slides/irow).

**Vrací:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```


Získá první sloupec buňky. Pouze ke čtení [IColumn](../../com.aspose.slides/icolumn).

**Vrací:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```


Vrací počet sloupců v mřížce nadřazené tabulky, které má aktuální buňka zabrat. Tato vlastnost umožňuje buňkám mít vzhled sloučení, protože přesahují svislé hranice ostatních buněk v tabulce. Pouze ke čtení int.

**Vrací:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```


Vrací počet řádků, které sloučená buňka zabírá. Používá se ve spojení s atributem vMerge u dalších buněk k určení počáteční buňky horizontálního sloučení. Pouze ke čtení int.

**Vrací:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Vrací textový rámec buňky. Pouze ke čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```


Vrací objekt rodičovské Tabulky pro buňku. Pouze ke čtení [ITable](../../com.aspose.slides/itable).

**Vrací:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```


Vrací true, pokud je buňka sloučena s jakoukoliv přizpůsobenou buňkou, jinak false. Pouze ke čtení boolean.

**Vrací:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```


Vrací objekt CellFormat, který obsahuje formátovací vlastnosti pro tuto buňku. Pouze ke čtení [ICellFormat](../../com.aspose.slides/icellformat).

**Vrací:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```


Rozděluje buňku na dvě buňky podle indexu sloupce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index sloupce. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```


Rozděluje buňku na dvě buňky podle indexu řádku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index řádku. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```


Rozděluje buňku podle výšky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| height | double | Výška řádku. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```


Rozděluje buňku podle šířky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| width | double | Šířka sloupce. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Vrací rodičovský snímek buňky. Pouze ke čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Vrací rodičovskou prezentaci buňky. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject