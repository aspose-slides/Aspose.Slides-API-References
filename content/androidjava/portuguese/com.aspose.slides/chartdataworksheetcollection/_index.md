---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de planilhas da pasta de trabalho de dados de gráfico.
type: docs
url: /pt/com.aspose.slides/chartdataworksheetcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Representa a coleção de planilhas da pasta de trabalho de dados de gráfico.

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

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna a planilha pelo índice. |
| [size()](#size--) | Retorna a contagem. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Copia para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

Retorna a planilha pelo índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da planilha na coleção. |

**Retorno:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instância de IChartDataWorksheet.
### size() {#size--}
```
public final int size()
```

Retorna a contagem. int somente leitura.

**Retorno:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. IDOMObject somente leitura.

**Retorno:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Copia para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array para o qual copiar. |
| arrayIndex | int | Índice para iniciar a cópia. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). boolean somente leitura.

**Retorno:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Object somente leitura.

**Retorno:**
java.lang.Object