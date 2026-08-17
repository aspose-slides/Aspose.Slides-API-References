---
title: TableFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt das Format einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/tableformat/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Stellt das Format einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Gibt ein Table Fill Properties-Objekt zurück. |
| [getTransparency()](#getTransparency--) | Liest oder setzt die Transparenz der Füllfarbe. |
| [setTransparency(float value)](#setTransparency-float-) | Liest oder setzt die Transparenz der Füllfarbe. |
| [getEffective()](#getEffective--) | Liest die effektiven Tabellformatierungseigenschaften mit Vererbung und angewendeten Tabellenstilen. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Gibt ein Table Fill Properties-Objekt zurück. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Liest oder setzt die Transparenz der Füllfarbe. Lese-/Schreibzugriff  float .

**Rückgabe:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Liest oder setzt die Transparenz der Füllfarbe. Lese-/Schreibzugriff  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


Liest die effektiven Tabellformatierungseigenschaften mit Vererbung und angewendeten Tabellenstilen.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Nur lesbar long.

**Rückgabe:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Gibt das übergeordnete IPresentationComponent zurück. Nur lesbar [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabe:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)