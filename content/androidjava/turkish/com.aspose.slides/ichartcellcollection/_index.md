---
title: IChartCellCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Veri içeren hücrelerin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartcellcollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Veri içeren hücrelerin koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Çalışma kitabındaki hücre setinin adresini döndürür. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Tüm hücrelerin metin değerlerinden oluşan birleştirilmiş dize. |
| [get_Item(int index)](#get-Item-int-) | İndekse göre bir hücre (IChartDataCell) döndürür. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Koleksiyona yeni bir hücre ekler. |
| [add(Object value)](#add-java.lang.Object-) | Belirtilen değerden [IChartDataCell](../../com.aspose.slides/ichartdatacell) oluşturur ve koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | İndekse göre koleksiyondan bir hücreyi kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki hücre sayısını alır. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Çalışma kitabındaki hücre setinin adresini döndürür.

**Döndürür:**
java.lang.String - Çalışma kitabındaki hücre setinin adresi String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Tüm hücrelerin metin değerlerinden oluşan birleştirilmiş dize.

**Döndürür:**
java.lang.String - Sonuç dizesi String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


İndekse göre bir hücre (IChartDataCell) döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Bir hücrenin indeksi. |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Veri içeren hücre.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Koleksiyona yeni bir hücre ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Eklenecek yeni hücre. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Belirtilen değerden [IChartDataCell](../../com.aspose.slides/ichartdatacell) oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object | Değer. |

--------------------

Bu yöntem, AUTO_DATA adında bir çalışma sayfası ekler ve tüm değerleri oraya ekler. [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) kullanarak Cell değerlerini ekler veya düzenlerseniz, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen maksimum değer sayısı 16711680'i geçmemelidir. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


İndekse göre koleksiyondan bir hücreyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak bir hücrenin indeksi. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki hücre sayısını alır. Salt okunur int.

**Döndürür:**
int