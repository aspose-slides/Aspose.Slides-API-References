---
title: IChartCellCollection
second_title: Aspose.Slides for Java API Referansı
description: Veri içeren hücrelerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartcellcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Veri içeren hücrelerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Çalışma kitabındaki hücre kümesinin adresini döndürür. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Tüm hücrelerin dize değerlerinden oluşan birleştirme dizesi. |
| [get_Item(int index)](#get-Item-int-) | İndeksine göre bir hücre (IChartDataCell) döndürür. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Koleksiyona yeni bir hücre ekler. |
| [add(Object value)](#add-java.lang.Object-) | Belirtilen değerden [IChartDataCell](../../com.aspose.slides/ichartdatacell) oluşturur ve koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | İndeksine göre koleksiyondan bir hücre kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki hücre sayısını alır. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

Çalışma kitabındaki hücre kümesinin adresini döndürür.

**Döndürür:**
java.lang.String - Çalışma kitabındaki hücre kümesinin adresi String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

Tüm hücrelerin dize değerlerinden oluşan birleştirme dizesi.

**Döndürür:**
java.lang.String - Sonuç dizesi String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

İndeksine göre bir hücre (IChartDataCell) döndürür.

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

Bu yöntem, AUTO_DATA adlı bir çalışma sayfası ekler ve tüm değerleri oraya ekler. Eğer [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) kullanarak Cell değerlerini ekler veya düzenlerseniz, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i geçmemelidir |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

İndeksine göre koleksiyondan bir hücre kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak hücrenin indeksi. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyondaki hücre sayısını alır. Salt okunur int.

**Döndürür:**
int