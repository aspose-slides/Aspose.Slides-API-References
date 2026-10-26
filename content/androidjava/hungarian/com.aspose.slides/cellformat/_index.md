---
title: CellFormat
second_title: Aspose.Slides for Android Java API hivatkozás
description: A táblacella formátumát reprezentálja.
type: docs
url: /hu/com.aspose.slides/cellformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

A táblacella formátumát reprezentálja.
## Metódusok

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Visszatér egy cella kitöltés tulajdonságait leíró objektummal. |
| [getBorderLeft()](#getBorderLeft--) | Visszatér egy bal oldali szegélyvonal tulajdonságait leíró objektummal. |
| [getBorderTop()](#getBorderTop--) | Visszatér egy felső szegélyvonal tulajdonságait leíró objektummal. |
| [getBorderRight()](#getBorderRight--) | Visszatér egy jobb oldali szegélyvonal tulajdonságait leíró objektummal. |
| [getBorderBottom()](#getBorderBottom--) | Visszatér egy alsó szegélyvonal tulajdonságait leíró objektummal. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Visszatér egy bal felső-jobb alsó átlóvonal tulajdonságait leíró objektummal. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Visszatér egy bal alsó-jobb felső átlóvonal tulajdonságait leíró objektummal. |
| [getEffective()](#getEffective--) | Lekéri a táblacella formázási tulajdonságait öröklődéssel és táblastílusokkal alkalmazva. |
| [getTransparency()](#getTransparency--) | Lekéri vagy beállítja a kitöltés szín átlátszóságát. |
| [setTransparency(float value)](#setTransparency-float-) | Lekéri vagy beállítja a kitöltés szín átlátszóságát. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Csak olvasható long.

**Returns:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Visszatér egy cella kitöltés tulajdonságait leíró objektummal. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Visszatér egy bal oldali szegélyvonal tulajdonságait leíró objektummal. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Visszatér egy felső szegélyvonal tulajdonságait leíró objektummal. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Visszatér egy jobb oldali szegélyvonal tulajdonságait leíró objektummal. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Visszatér egy alsó szegélyvonal tulajdonságait leíró objektummal. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Visszatér egy bal felső-jobb alsó átlóvonal tulajdonságait leíró objektummal. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Visszatér egy bal alsó-jobb felső átlóvonal tulajdonságait leíró objektummal. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Lekéri a táblacella formázási tulajdonságait öröklődéssel és táblastílusokkal alkalmazva.

--------------------

> ```
> Ez a példa bemutatja a hatékony kitöltési formátum lekérését a táblázat különböző logikai részeihez.
>  Vegye figyelembe, hogy a cella formázása mindig nagyobb prioritással bír, mint a sor formázása, a sor nagyobb, mint az oszlop, az oszlop nagyobb, mint a teljes táblázat.
>  Így végül a CellFormatEffectiveData tulajdonságok mindig a táblázat rajzolásához használatosak. Az alábbi kód csak egy API példát mutat.
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


**Returns:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Lekéri vagy beállítja a kitöltés szín átlátszóságát. Olvasás/írás  float .

**Returns:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Lekéri vagy beállítja a kitöltés szín átlátszóságát. Olvasás/írás  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |