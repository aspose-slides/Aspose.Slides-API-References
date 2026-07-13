---
title: Table
second_title: Aspose.Slides voor Android via Java API-referentie
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

Stelt een tabel op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Retourneert de cel op de opgegeven kolom- en rij-indexen. |
| [getRows()](#getRows--) | Retourneert de verzameling rijen. |
| [getColumns()](#getColumns--) | Retourneert de verzameling kolommen. |
| [getTableFormat()](#getTableFormat--) | Retourneert het TableFormat-object dat de opmaak-eigenschappen voor deze tabel bevat. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Voegt naastliggende cellen samen. |
| [getStylePreset()](#getStylePreset--) | Haalt de ingebouwde tabelstijl op of stelt deze in. |
| [setStylePreset(int value)](#setStylePreset-int-) | Haalt de ingebouwde tabelstijl op of stelt deze in. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of de tabel een rechts-naar-links leesvolgorde heeft. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Bepaalt of de tabel een rechts-naar-links leesvolgorde heeft. |
| [getFirstRow()](#getFirstRow--) | Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. |
| [getFirstCol()](#getFirstCol--) | Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. |
| [getLastRow()](#getLastRow--) | Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak. |
| [getLastCol()](#getLastCol--) | Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Bepaalt of de even rijen met een andere opmaak moeten worden getekend. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Bepaalt of de even rijen met een andere opmaak moeten worden getekend. |
| [getVerticalBanding()](#getVerticalBanding--) | Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Stelt gedefinieerde deelopmaak-eigenschappen in voor alle delen van tabelcellen. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Stelt gedefinieerde alinea-opmaak-eigenschappen in voor alle alinea's van tabelcellen. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Stelt gedefinieerde tekstframe-opmaak-eigenschappen in voor alle tekstframes van tabelcellen. |
| [getFillFormat()](#getFillFormat--) | Retourneert een TableFormat.FillFormat-object dat de vullingsopmaak voor de tabel bevat. |
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


Retourneert de verzameling rijen. Alleen-lezen [IRowCollection](../../com.aspose.slides/irowcollection).

**Retour:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```


Retourneert de verzameling kolommen. Alleen-lezen [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Retour:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```


Retourneert het TableFormat-object dat de opmaak-eigenschappen voor deze tabel bevat. Alleen-lezen [ITableFormat](../../com.aspose.slides/itableformat).

**Retour:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Voegt naastliggende cellen samen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cel om te combineren. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cel om te combineren. |
| allowSplitting | boolean | True om het splitsen van cellen toe te staan. |

**Retour:**
[ICell](../../com.aspose.slides/icell) - Samengevoegde cel.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```


Lezen/Schrijven ingebouwde tabelstijl [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Retour:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```


Lezen/Schrijven ingebouwde tabelstijl [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```


Bepaalt of de tabel een rechts-naar-links leesvolgorde heeft. Lezen-schrijven boolean .

**Retour:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```


Bepaalt of de tabel een rechts-naar-links leesvolgorde heeft. Lezen-schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```


Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean .

**Retour:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```


Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```


Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean .

**Retour:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```


Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```


Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean .

**Retour:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```


Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```


Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean .

**Retour:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```


Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```


Bepaalt of de even rijen met een andere opmaak moeten worden getekend. Lezen-schrijven boolean .

**Retour:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```


Bepaalt of de even rijen met een andere opmaak moeten worden getekend. Lezen-schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```


Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. Lezen-schrijven boolean .

**Retour:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```


Bepaalt of de even kolommen met een andere opmaak moeten worden getekend. Lezen-schrijven boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Stelt gedefinieerde deelopmaak-eigenschappen in voor alle delen van tabelcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-object met de benodigde eigenschappen ingesteld. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Stelt gedefinieerde alinea-opmaak-eigenschappen in voor alle alinea's van tabelcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-object met de benodigde eigenschappen ingesteld. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Stelt gedefinieerde tekstframe-opmaak-eigenschappen in voor alle tekstframes van tabelcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-object met de benodigde eigenschappen ingesteld. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```


Retourneert een TableFormat.FillFormat-object dat de vullingsopmaak voor de tabel bevat. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)