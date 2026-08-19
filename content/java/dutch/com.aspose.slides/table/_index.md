---
title: Table
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een tabel op een dia.
type: docs
url: /nl/com.aspose.slides/table/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Vertegenwoordigt een tabel op een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Retourneert de cel op de opgegeven kolom- en rij-indexen. |
| [getRows()](#getRows--) | Retourneert de collectie van rijen. |
| [getColumns()](#getColumns--) | Retourneert de collectie van kolommen. |
| [getTableFormat()](#getTableFormat--) | Retourneert het TableFormat-object dat opmaak-eigenschappen voor deze tabel bevat. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Voegt aangrenzende cellen samen. |
| [getStylePreset()](#getStylePreset--) | Leest of stelt de ingebouwde tabelstijl in. |
| [setStylePreset(int value)](#setStylePreset-int-) | Leest of stelt de ingebouwde tabelstijl in. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of de tabel van rechts-naar-links leesvolgorde heeft. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Bepaalt of de tabel van rechts-naar-links leesvolgorde heeft. |
| [getFirstRow()](#getFirstRow--) | Bepaalt of de eerste rij van een tabel met een speciale opmaak moet worden getekend. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bepaalt of de eerste rij van een tabel met een speciale opmaak moet worden getekend. |
| [getFirstCol()](#getFirstCol--) | Bepaalt of de eerste kolom van een tabel met een speciale opmaak moet worden getekend. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bepaalt of de eerste kolom van een tabel met een speciale opmaak moet worden getekend. |
| [getLastRow()](#getLastRow--) | Bepaalt of de laatste rij van een tabel met een speciale opmaak moet worden getekend. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bepaalt of de laatste rij van een tabel met een speciale opmaak moet worden getekend. |
| [getLastCol()](#getLastCol--) | Bepaalt of de laatste kolom van een tabel met een speciale opmaak moet worden getekend. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bepaalt of de laatste kolom van een tabel met een speciale opmaak moet worden getekend. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Bepaalt of de even rijen met een andere opmaak moeten worden getekend. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Bepaalt of de even rijen met een andere opmaak moeten worden getekend. |
| [getVerticalBanding()](#getVerticalBanding--) | Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Stelt gedefinieerde gedeelte-opmaak-eigenschappen in voor alle delen van tabelcellen. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Stelt gedefinieerde alinea-opmaak-eigenschappen in voor alle alinea's van tabelcellen. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Stelt gedefinieerde tekstframe-opmaak-eigenschappen in voor alle tekstframes van tabelcellen. |
| [getFillFormat()](#getFillFormat--) | Retourneert een TableFormat.FillFormat-object dat de vul-opmaak voor de tabel bevat. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Retourneert de cel op de opgegeven kolom- en rij-indexen. Alleen-lezen [Cell](../../com.aspose.slides/cell).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Retour:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Retourneert de collectie van rijen. Alleen-lezen [IRowCollection](../../com.aspose.slides/irowcollection).

**Retour:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Retourneert de collectie van kolommen. Alleen-lezen [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Retour:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Retourneert het TableFormat-object dat opmaak-eigenschappen voor deze tabel bevat. Alleen-lezen [ITableFormat](../../com.aspose.slides/itableformat).

**Retour:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Voegt aangrenzende cellen samen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

**Retour:**
[ICell](../../com.aspose.slides/icell) - Samengevoegde cel.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Leest of stelt de ingebouwde tabelstijl in. Lezen/Schrijven [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Retour:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Leest of stelt de ingebouwde tabelstijl in. Lezen/Schrijven [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Bepaalt of de tabel van rechts-naar-links leesvolgorde heeft. Lezen/Schrijven boolean.

**Retour:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Bepaalt of de tabel van rechts-naar-links leesvolgorde heeft. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Bepaalt of de eerste rij van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven boolean.

**Retour:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Bepaalt of de eerste rij van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Bepaalt of de eerste kolom van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven boolean.

**Retour:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Bepaalt of de eerste kolom van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Bepaalt of de laatste rij van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven boolean.

**Retour:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Bepaalt of de laatste rij van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Bepaalt of de laatste kolom van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven boolean.

**Retour:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Bepaalt of de laatste kolom van een tabel met een speciale opmaak moet worden getekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Bepaalt of de even rijen met een andere opmaak moeten worden getekend. Lezen/Schrijven boolean.

**Retour:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Bepaalt of de even rijen met een andere opmaak moeten worden getekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. Lezen/Schrijven boolean.

**Retour:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Stelt gedefinieerde gedeelte-opmaak-eigenschappen in voor alle delen van tabelcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Stelt gedefinieerde alinea-opmaak-eigenschappen in voor alle alinea's van tabelcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Stelt gedefinieerde tekstframe-opmaak-eigenschappen in voor alle tekstframes van tabelcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Retourneert een TableFormat.FillFormat-object dat de vul-opmaak voor de tabel bevat. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)