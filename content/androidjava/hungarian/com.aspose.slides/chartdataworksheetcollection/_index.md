---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A diagramadatok munkafüzetének munkalapjainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/chartdataworksheetcollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

A diagramadatok munkafüzetének munkalapjainak gyűjteményét képviseli.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a munkalapot index szerint. |
| [size()](#size--) | Visszaadja a darabszámot. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Másolja a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

Visszaadja a munkalapot index szerint.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A munkalap indexe a gyűjteményben. |

**Visszatérési érték:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Az IChartDataWorksheet egy példánya.
### size() {#size--}
```
public final int size()
```

Visszaadja a darabszámot. Csak olvasható int.

**Visszatérési érték:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator amely a gyűjtemény bejárására használható.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - A IGenericEnumerator amely a gyűjtemény bejárására használható.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Másolja a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | A tömb, amelybe másolni kell. |
| arrayIndex | int | Az index, ahonnan a másolás kezdődik. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object