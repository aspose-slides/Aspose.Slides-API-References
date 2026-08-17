---
title: ChartCellCollection
second_title: Aspose.Slides for Java API Referansı
description: Veri içeren hücrelerden oluşan bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/chartcellcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Veri içeren hücrelerden oluşan bir koleksiyonu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Çalışma kitabındaki hücre kümesinin adresini döndürür. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Tüm hücrelerin dize değerlerinden oluşan birleştirme dizesi. |
| [get_Item(int index)](#get-Item-int-) | İndeksine göre bir hücre (IChartDataCell) döndürür. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Koleksiyona yeni bir hücre ekler. |
| [add(Object value)](#add-java.lang.Object-) | [ChartDataCell](../../com.aspose.slides/chartdatacell) öğesini belirtilen değerden oluşturur ve koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | İndeksine göre koleksiyondan bir hücreyi kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki hücre sayısını alır. |
| [iterator()](#iterator--) | Koleksiyonda döngü yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Çalışma kitabındaki hücre kümesinin adresini döndürür.

**Döndürür:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Tüm hücrelerin dize değerlerinden oluşan birleştirme dizesi.

**Döndürür:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


İndeksine göre bir hücre (IChartDataCell) döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Bir hücrenin indeksi. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Veri içeren hücre.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Koleksiyona yeni bir hücre ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Eklenecek yeni hücre. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


[ChartDataCell](../../com.aspose.slides/chartdatacell) öğesini belirtilen değerden oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object | Değer.

--------------------

Bu yöntem, AUTO_DATA adında bir çalışma sayfası ekler ve tüm değerleri oraya ekler. Eğer [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) kullanarak Hücre değerlerini eklemek veya düzenlemek isterseniz, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i aşmamalıdır.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


İndeksine göre koleksiyondan bir hücreyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak hücrenin indeksi. |

### getCount() {#getCount--}
```
public final int getCount()
```


Koleksiyondaki hücre sayısını alır. Salt-okunur int.

**Döndürür:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Koleksiyonda döngü yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Koleksiyonda döngü yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Tüm koleksiyon için bir java.util.Iterator.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject