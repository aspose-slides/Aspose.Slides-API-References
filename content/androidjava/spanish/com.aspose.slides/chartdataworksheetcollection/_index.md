---
title: ChartDataWorksheetCollection
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa la colección de hojas de cálculo del libro de datos del gráfico.
type: docs
url: /es/com.aspose.slides/chartdataworksheetcollection/
---
**Herencia:**
java.lang.Object

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Representa la colección de hojas de cálculo del libro de datos del gráfico.

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
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la hoja de cálculo por índice. |
| [size()](#size--) | Devuelve el recuento. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Copiar al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```


Devuelve la hoja de cálculo por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la hoja de cálculo en la colección. |

**Devuelve:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instancia de IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```


Devuelve el recuento. int de solo lectura.

**Devuelve:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. IDOMObject de solo lectura.

**Devuelve:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```


Copiar al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array al que copiar. |
| arrayIndex | int | Índice para iniciar la copia. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). boolean de solo lectura.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Devuelve una raíz de sincronización. Object de solo lectura.

**Devuelve:**
java.lang.Object