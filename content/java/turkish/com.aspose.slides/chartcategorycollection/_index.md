---
title: ChartCategoryCollection
second_title: Aspose.Slides Java API Referansı
description: Koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/chartcategorycollection/
---
**Kalıtım:**  
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**  
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)  
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

[ChartCategory](../../com.aspose.slides/chartcategory) koleksiyonunu temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indekste bulunan öğeyi alır. |
| [getUseCells()](#getUseCells--) | Doğru ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Doğru ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Kullanılan kategori gruplama seviyelerinin sayısını döndürür. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Kategori koleksiyonda mevcutsa, onu döndürür. |
| [add(Object value)](#add-java.lang.Object-) | Değerden yeni [ChartCategory](../../com.aspose.slides/chartcategory) oluşturur ve koleksiyona ekler. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Belirtilen [ChartCategory](../../com.aspose.slides/chartcategory) öğesini arar ve tüm Collection içinde ilk oluşumun sıfır tabanlı indeksini döndürür. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Belirtilen değeri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Verilen indekste bulunan öğeyi kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [size()](#size--) | Koleksiyondaki öğe sayısını döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Listeye erişimin eşzamanlı (thread safe) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Koleksiyona erişimi eşzamanlamak için kullanılabilecek bir nesne döndürür. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Belirtilen indekste bulunan öğeyi alır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Belirtilen indekste bulunan öğe.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Doğru ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir). Yanlış ise çalışma sayfası değerleri depolamak için kullanılmaz (ve bu durumda çok seviyeli kategoriler desteklenmez). Okuma/yazma boolean.

**Döndürür:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Doğru ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir). Yanlış ise çalışma sayfası değerleri depolamak için kullanılmaz (ve bu durumda çok seviyeli kategoriler desteklenmez). Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Kullanılan kategori gruplama seviyelerinin sayısını döndürür. Çok seviyeli kategoriler için birden fazla olabilir. Salt okunur int.

**Döndürür:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Kategori koleksiyonda mevcutsa, onu döndürür. Aksi takdirde [IChartDataCell](../../com.aspose.slides/ichartdatacell) üzerinden yeni bir grafik kategorisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Grafik kategorisi oluşturmak için kullanılan hücre. |

**Döndürür:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Eklenen ya da mevcut kategori.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Değerden yeni [ChartCategory](../../com.aspose.slides/chartcategory) oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.Object | Değer. |

--------------------

Bu yöntem, AUTO_DATA adlı çalışma sayfasını ekler ve tüm değerleri oraya ekler. Eğer [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) kullanarak hücre değerlerini ekleyip düzenliyorsanız, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen maksimum değer sayısı 16711680'i geçmemelidir.

**Döndürür:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Eklenen [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Belirtilen [ChartCategory](../../com.aspose.slides/chartcategory) öğesini arar ve tüm Collection içinde ilk oluşumun sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Grafik kategorisi. |

**Döndürür:**
int - Değerin tüm CollectionBase içinde ilk oluşumunun sıfır tabanlı indeksi, bulunursa; aksi takdirde -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Belirtilen değeri kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Değer. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verilen indekste bulunan öğeyi kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak kategorinin indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Tüm koleksiyon için bir java.util.Iterator.

### size() {#size--}
```
public final int size()
```

Koleksiyondaki öğe sayısını döndürür. Salt okunur int.

**Döndürür:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Listeye erişimin eşzamanlı (thread safe) olup olmadığını belirten bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Koleksiyona erişimi eşzamanlamak için kullanılabilecek bir nesne döndürür. Salt okunur Object.

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object