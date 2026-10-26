---
title: ICell
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Zastupuje buňku v tabulce.
type: docs
url: /cs/com.aspose.slides/icell/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Zastupuje buňku v tabulce.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Vrací vzdálenost od levé strany tabulky k levé straně buňky. |
| [getOffsetY()](#getOffsetY--) | Vrací vzdálenost od horní strany tabulky k horní straně buňky. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Vrací index první řady, kterou buňka pokrývá. |
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
| [getAnchorCenter()](#getAnchorCenter--) | Určuje, zda je textové pole vycentrováno uvnitř buňky. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Určuje, zda je textové pole vycentrováno uvnitř buňky. |
| [getFirstColumn()](#getFirstColumn--) | Získá první sloupec buňky. |
| [getFirstRow()](#getFirstRow--) | Získá první řadu buňky. |
| [getColSpan()](#getColSpan--) | Vrací počet sloupců v mřížce nadřazené tabulky, které má aktuální buňka zabírat. |
| [getRowSpan()](#getRowSpan--) | Vrací počet řad, které sloučená buňka zabírá. |
| [getTextFrame()](#getTextFrame--) | Vrací textový rámec buňky. |
| [getTable()](#getTable--) | Vrací objekt nadřazené Tabulky pro buňku. |
| [isMergedCell()](#isMergedCell--) | Vrací true, pokud je buňka sloučena s jakoukoliv jinou buňkou, jinak false. |
| [getCellFormat()](#getCellFormat--) | Vrací objekt CellFormat, který obsahuje formátovací vlastnosti pro tuto buňku. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Rozdělí buňku na dvě buňky podle indexu sloupce. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Rozdělí buňku na dvě buňky podle indexu řady. |
| [splitByHeight(double height)](#splitByHeight-double-) | Rozdělí buňku podle výšky. |
| [splitByWidth(double width)](#splitByWidth-double-) | Rozdělí buňku podle šířky. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```


Vrací vzdálenost od levé strany tabulky k levé straně buňky. Pouze pro čtení double.

**Vrací:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```


Vrací vzdálenost od horní strany tabulky k horní straně buňky. Pouze pro čtení double.

**Vrací:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```


Vrací index první řady, kterou buňka pokrývá. Pouze pro čtení int.

**Vrací:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```


Vrací index první sloupce, který buňka pokrývá. Pouze pro čtení int.

**Vrací:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Vrací šířku buňky. Pouze pro čtení double.

**Vrací:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Vrací výšku buňky. Pouze pro čtení double.

**Vrací:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Vrací minimální výšku buňky. Jedná se o součet minimálních výšek všech řad, které buňka pokrývá. Pouze pro čtení double.

**Vrací:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Vrací nebo nastavuje levý okraj v TextFrame. Čtení/Zápis double.

**Vrací:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Vrací nebo nastavuje levý okraj v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Vrací nebo nastavuje pravý okraj v TextFrame. Čtení/Zápis double.

**Vrací:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Vrací nebo nastavuje pravý okraj v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Vrací nebo nastavuje horní okraj v TextFrame. Čtení/Zápis double.

**Vrací:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Vrací nebo nastavuje horní okraj v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Vrací nebo nastavuje spodní okraj v TextFrame. Čtení/Zápis double.

**Vrací:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Vrací nebo nastavuje spodní okraj v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Vrací nebo nastavuje typ svislého textu. Čtení/Zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Vrací nebo nastavuje typ svislého textu. Čtení/Zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```


Vrací nebo nastavuje typ ukotvení textu. Čtení/Zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```


Vrací nebo nastavuje typ ukotvení textu. Čtení/Zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```


Určuje, zda je textové pole vycentrováno uvnitř buňky. Čtení/Zápis boolean.

**Vrací:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```


Určuje, zda je textové pole vycentrováno uvnitř buňky. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```


Získá první sloupec buňky. Pouze pro čtení [IColumn](../../com.aspose.slides/icolumn).

**Vrací:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```


Získá první řadu buňky. Pouze pro čtení [IRow](../../com.aspose.slides/irow).

**Vrací:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```


Vrací počet sloupců v mřížce nadřazené tabulky, které má aktuální buňka zabírat. Tato vlastnost umožňuje buňkám vypadat, jako by byly sloučeny, protože přesahují vertikální hranice ostatních buněk v tabulce. Pouze pro čtení int.

**Vrací:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```


Vrací počet řad, které sloučená buňka zabírá. Používá se ve spojení s atributem vMerge u jiných buněk k určení počáteční buňky horizontálního sloučení. Pouze pro čtení int.

**Vrací:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Vrací textový rámec buňky. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```


Vrací objekt nadřazené Tabulky pro buňku. Pouze pro čtení [ITable](../../com.aspose.slides/itable).

**Vrací:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```


Vrací true, pokud je buňka sloučena s jakoukoliv upravenou buňkou, jinak false. Pouze pro čtení boolean.

**Vrací:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```


Vrací objekt CellFormat, který obsahuje formátovací vlastnosti pro tuto buňku. Pouze pro čtení [ICellFormat](../../com.aspose.slides/icellformat).

**Vrací:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```


Rozdělí buňku na dvě buňky podle indexu sloupce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index sloupce. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```


Rozdělí buňku na dvě buňky podle indexu řady.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index řady. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```


Rozdělí buňku podle výšky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| height | double | Výška řady. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```


Rozdělí buňku podle šířky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| width | double | Šířka sloupce. |