---
title: ChartCellCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Veri içeren hücrelerin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/chartcellcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Veri içeren hücrelerin koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Çalışma kitabındaki hücre kümesinin adresini döndürür. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Tüm hücrelerin dizgi değerlerinden birleştirilmiş dize. |
| [get_Item(int index)](#get-Item-int-) | İndeksine göre bir hücre (IChartDataCell) döndürür. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Koleksiyona yeni bir hücre ekler. |
| [add(Object value)](#add-java.lang.Object-) | Belirtilen değerden [ChartDataCell](../../com.aspose.slides/chartdatacell) oluşturur ve koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | İndeksine göre koleksiyondan bir hücre kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki hücre sayısını alır. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Çalışma kitabındaki hücre kümesinin adresini döndürür.

**Returns:**
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

Tüm hücrelerin dizgi değerlerinden birleştirilmiş dize.

**Returns:**
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

İndeksine göre bir hücre (IChartDataCell) döndürür.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Hücrenin indeksi. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Verili hücre.

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Koleksiyona yeni bir hücre ekler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Eklenecek yeni hücre. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Belirtilen değerden [ChartDataCell](../../com.aspose.slides/chartdatacell) oluşturur ve koleksiyona ekler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Değer.

--------------------

Bu yöntem, AUTO_DATA adıyla bir çalışma sayfası ekler ve tüm değerleri oraya ekler. [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) kullanarak Hücre değerlerini ekler ya da düzenlerseniz, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i geçmemelidir |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

İndeksine göre koleksiyondan bir hücre kaldırır.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Kaldırılacak hücrenin indeksi. |

### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyondaki hücre sayısını alır. Yalnızca okunabilir int.

**Returns:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Koleksiyon üzerinde yineleme yapan bir enumerator döndürür.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Koleksiyon üzerinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Tüm koleksiyon için bir java.util.Iterator.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunabilir IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject