---
title: IChartCategoryCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/ichartcategorycollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

[IChartCategory](../../com.aspose.slides/ichartcategory) koleksiyonunu temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [getUseCells()](#getUseCells--) | Doğru ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok düzeyli kategoriler desteklenir). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Doğru ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok düzeyli kategoriler desteklenir). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Kullanılan kategori gruplama seviyelerinin sayısını döndürür. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Kategori koleksiyonda mevcutsa, onu döndürür. |
| [add(Object value)](#add-java.lang.Object-) | [IChartCategory](../../com.aspose.slides/ichartcategory) öğesini değerden oluşturur ve koleksiyona ekler. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Belirtilen [IChartCategory](../../com.aspose.slides/ichartcategory) öğesini arar ve tüm Collection içinde ilk oluşumun sıfır tabanlı indeksini döndürür. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Belirtilen değeri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Verilen indeksteki öğeyi kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Belirtilen dizindeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Belirtilen dizindeki öğe.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Doğru ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok düzeyli kategoriler desteklenir). Yanlış ise çalışma sayfası değerleri depolamak için kullanılmaz (ve bu durumda çok düzeyli kategoriler desteklenmez). Okunur/yazılabilir boolean.

**Dönüş Değeri:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Doğru ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok düzeyli kategoriler desteklenir). Yanlış ise çalışma sayfası değerleri depolamak için kullanılmaz (ve bu yöntem çok düzeyli kategorileri desteklemez). Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Kullanılan kategori gruplama seviyelerinin sayısını döndürür. Çok düzeyli kategoriler için birden fazla olabilir. Salt okunur int.

**Dönüş Değeri:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Kategori koleksiyonda mevcutsa, onu döndürür. Aksi takdirde [IChartDataCell](../../com.aspose.slides/ichartdatacell) öğesinden yeni bir grafik kategorisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Grafik kategorisi oluşturmak için kullanılan hücre. |

**Dönüş Değeri:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Eklenen ya da mevcut kategori.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

[IChartCategory](../../com.aspose.slides/ichartcategory) öğesini değerden oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object | Değer.

--------------------

Bu yöntem AUTO_DATA adında bir çalışma sayfası ekler ve tüm değerleri oraya ekler. [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) kullanarak hücre değerlerini ekler veya düzenlerseniz, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen değer sayısı 16711680'i aşmamalıdır.

**Dönüş Değeri:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Eklenen [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Belirtilen [IChartCategory](../../com.aspose.slides/ichartcategory) öğesini arar ve tüm Collection içinde ilk oluşumun sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Grafik kategorisi. |

**Dönüş Değeri:**
int - Değerin tüm CollectionBase içindeki ilk oluşumunun sıfır tabanlı indeksi, bulunursa; aksi takdirde -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Belirtilen değeri kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Değer. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak kategorinin indeksi. |
### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.