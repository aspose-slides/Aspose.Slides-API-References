---
title: CellFormat
second_title: Aspose.Slides Java API Referenciája
description: A táblázatcella formátumát képviseli.
type: docs
url: /hu/com.aspose.slides/cellformat/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

A táblázatcellá formátumát képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Visszaad egy cella kitöltési tulajdonság objektumot. |
| [getBorderLeft()](#getBorderLeft--) | Visszaad egy bal szegélyvonal tulajdonság objektumot. |
| [getBorderTop()](#getBorderTop--) | Visszaad egy felső szegélyvonal tulajdonság objektumot. |
| [getBorderRight()](#getBorderRight--) | Visszaad egy jobb oldali szegélyvonal tulajdonság objektumot. |
| [getBorderBottom()](#getBorderBottom--) | Visszaad egy alsó szegélyvonal tulajdonság objektumot. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Visszaad egy bal felső sarokból jobb alsó sarokba ívelő vonal tulajdonság objektumot. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Visszaad egy bal alsó sarokból jobb felső sarokba ívelő vonal tulajdonság objektumot. |
| [getEffective()](#getEffective--) | Lekéri a hatékony táblázatcella formázási tulajdonságokat öröklődéssel és alkalmazott táblázatstílusokkal. |
| [getTransparency()](#getTransparency--) | Lekéri vagy beállítja a kitöltő szín átlátszóságát. |
| [setTransparency(float value)](#setTransparency-float-) | Lekéri vagy beállítja a kitöltő szín átlátszóságát. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Csak olvasható long.

**Visszaad:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Visszaad egy cella kitöltési tulajdonság objektumot. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszaad:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Visszaad egy bal szegélyvonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszaad:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Visszaad egy felső szegélyvonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszaad:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Visszaad egy jobb oldali szegélyvonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszaad:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Visszaad egy alsó szegélyvonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszaad:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Visszaad egy bal felső sarokból jobb alsó sarokba ívelő vonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszaad:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Visszaad egy bal alsó sarokból jobb felső sarokba ívelő vonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszaad:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Lekéri a hatékony táblázatcella formázási tulajdonságokat öröklődéssel és alkalmazott táblázatstílusokkal.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszaad:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Lekéri vagy beállítja a kitöltő szín átlátszóságát. Olvasás/írás  float .

**Visszaad:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Lekéri vagy beállítja a kitöltő szín átlátszóságát. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |