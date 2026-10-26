---
title: TableFormat
second_title: Aspose.Slides Androidra Java API hivatkozás
description: A táblázat formátumát képviseli.
type: docs
url: /hu/com.aspose.slides/tableformat/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

A táblázat formátumát képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Visszaad egy táblázat kitöltési tulajdonság objektumot. |
| [getTransparency()](#getTransparency--) | Lekérdezi vagy beállítja a kitöltő szín átlátszóságát. |
| [setTransparency(float value)](#setTransparency-float-) | Lekérdezi vagy beállítja a kitöltő szín átlátszóságát. |
| [getEffective()](#getEffective--) | Lekérdezi a tényleges táblázat formázási tulajdonságokat öröklődéssel és táblázatstílusok alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Visszaad egy táblázat kitöltési tulajdonság objektumot. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Lekérdezi vagy beállítja a kitöltő szín átlátszóságát. Olvasás/írás  float .

**Visszatér:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Lekérdezi vagy beállítja a kitöltő szín átlátszóságát. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Lekérdezi a tényleges táblázat formázási tulajdonságokat öröklődéssel és táblázatstílusok alkalmazásával.

--------------------

> ```
> Ez a példa bemutatja a különböző táblázati logikai részek hatékony kitöltésformátumának lekérését.
>  Felhívjuk a figyelmet, hogy a cellaformázás mindig magasabb prioritással bír, mint a sorformázás, a sor - magasabb, mint az oszlop, az oszlop - magasabb, mint a teljes táblázat.
>  Tehát végül a CellFormatEffectiveData tulajdonságok mindig a táblázat kirajzolásához használatosak. A következő kód csak egy API példa.
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


**Visszatér:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Visszaadja az IPresentationComponent szülőt. Csak olvasható [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatér:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)