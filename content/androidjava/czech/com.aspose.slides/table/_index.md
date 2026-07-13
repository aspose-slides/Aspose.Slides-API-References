---
title: Table
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje tabulku na snímku.
type: docs
url: /cs/com.aspose.slides/table/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Představuje tabulku na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Vrací buňku na určených indexech sloupce a řádku. |
| [getRows()](#getRows--) | Vrací kolekci řádků. |
| [getColumns()](#getColumns--) | Vrací kolekci sloupců. |
| [getTableFormat()](#getTableFormat--) | Vrací objekt TableFormat, který obsahuje vlastnosti formátování pro tuto tabulku. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Spojuje sousední buňky. |
| [getStylePreset()](#getStylePreset--) | Získává nebo nastavuje vestavěný styl tabulky. |
| [setStylePreset(int value)](#setStylePreset-int-) | Získává nebo nastavuje vestavěný styl tabulky. |
| [getRightToLeft()](#getRightToLeft--) | Určuje, zda má tabulka směr čtení zprava doleva. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Určuje, zda má tabulka směr čtení zprava doleva. |
| [getFirstRow()](#getFirstRow--) | Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. |
| [getFirstCol()](#getFirstCol--) | Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. |
| [getLastRow()](#getLastRow--) | Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. |
| [getLastCol()](#getLastCol--) | Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. |
| [getVerticalBanding()](#getVerticalBanding--) | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Nastavuje definované vlastnosti formátu úryvku na všechny úryvky buněk tabulky. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Nastavuje definované vlastnosti formátu odstavce na všechny odstavce buněk tabulky. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Nastavuje definované vlastnosti formátu textového rámce na všechny textové rámy buněk tabulky. |
| [getFillFormat()](#getFillFormat--) | Vrací objekt TableFormat.FillFormat obsahující výplňové formátování pro Tabulku. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Vrací buňku na určených indexech sloupce a řádku. Pouze pro čtení [Cell](../../com.aspose.slides/cell).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Vrací:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Vrací kolekci řádků. Pouze pro čtení [IRowCollection](../../com.aspose.slides/irowcollection).

**Vrací:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Vrací kolekci sloupců. Pouze pro čtení [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Vrací:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Vrací objekt TableFormat, který obsahuje vlastnosti formátování pro tuto tabulku. Pouze pro čtení [ITableFormat](../../com.aspose.slides/itableformat).

**Vrací:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Spojuje sousední buňky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Buňka ke sloučení. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Buňka ke sloučení. |
| allowSplitting | boolean | True, pokud má být povoleno rozdělení buněk. |

**Vrací:**
[ICell](../../com.aspose.slides/icell) - Sloučená buňka.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Získává nebo nastavuje vestavěný styl tabulky. Čtení/zápis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Vrací:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Získává nebo nastavuje vestavěný styl tabulky. Čtení/zápis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Určuje, zda má tabulka směr čtení zprava doleva. Čtení/zápis  boolean .

**Vrací:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Určuje, zda má tabulka směr čtení zprava doleva. Čtení/zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. Čtení/zápis  boolean .

**Vrací:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. Čtení/zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. Čtení/zápis  boolean .

**Vrací:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. Čtení/zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. Čtení/zápis  boolean .

**Vrací:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. Čtení/zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. Čtení/zápis  boolean .

**Vrací:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. Čtení/zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Čtení/zápis  boolean .

**Vrací:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Čtení/zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Čtení/zápis  boolean .

**Vrací:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Čtení/zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Nastavuje definované vlastnosti formátu úryvku na všechny úryvky buněk tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Objekt IPortionFormat s nastavenými nezbytnými vlastnostmi. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Nastavuje definované vlastnosti formátu odstavce na všechny odstavce buněk tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Objekt IParagraphFormat s nastavenými nezbytnými vlastnostmi. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Nastavuje definované vlastnosti formátu textového rámce na všechny textové rámy buněk tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Objekt ITextFrameFormat s nastavenými nezbytnými vlastnostmi. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Vrací objekt TableFormat.FillFormat obsahující výplňové formátování pro Tabulku. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)