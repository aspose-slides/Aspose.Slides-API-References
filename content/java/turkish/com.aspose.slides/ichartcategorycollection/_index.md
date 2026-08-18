---
title: IChartCategoryCollection
second_title: Aspose.Slides Java API Referansı
description: Koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/ichartcategorycollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

[IChartCategory](../../com.aspose.slides/ichartcategory) koleksiyonunu temsil eder
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getUseCells()](#getUseCells--) | Eğer true ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Eğer true ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Kullanılan kategori gruplanma seviyelerinin sayısını döndürür. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Kategori koleksiyonda mevcutsa, onu döndürür. |
| [add(Object value)](#add-java.lang.Object-) | Değerden yeni bir [IChartCategory](../../com.aspose.slides/ichartcategory) oluşturur ve koleksiyona ekler. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Belirtilen [IChartCategory](../../com.aspose.slides/ichartcategory) içinde arama yapar ve tüm Koleksiyon içinde ilk oluşumun sıfır tabanlı indeksini döndürür. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Belirtilen değeri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Verilen indeksteki öğeyi kaldırır. |
| [clear()](#clear--) | Koleksiyondan tüm öğeleri kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```


Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Belirtilen indeksteki öğe.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```


Eğer true ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir). Eğer false ise çalışma sayfası değerleri depolamak için kullanılmaz (ve bu durumda çok seviyeli kategoriler desteklenmez). Okunur/yazılır boolean.

**Dönüş Değeri:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```


Eğer true ise çalışma sayfası kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir). Eğer false ise çalışma sayfası değerleri depolamak için kullanılmaz (ve bu durumda çok seviyeli kategoriler desteklenmez). Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```


Kullanılan kategori gruplanma seviyelerinin sayısını döndürür. Çok seviyeli kategoriler için birden fazla olabilir. Salt okunur int.

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
[IChartCategory](../../com.aspose.slides/ichartcategory) - Eklenen veya mevcut kategori.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```


Değerden yeni bir [IChartCategory](../../com.aspose.slides/ichartcategory) oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object | Değer. |

--------------------

Bu yöntem AUTO_DATA adlı çalışma sayfasını ekler ve tüm değerleri oraya ekler. [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) kullanarak hücre değerlerini ekler veya düzenlerseniz, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i geçmemelidir.

**Dönüş Değeri:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Eklenen [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```


Belirtilen [IChartCategory](../../com.aspose.slides/ichartcategory) içinde arama yapar ve tüm Collection içinde ilk oluşumun sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Grafik kategorisi. |

**Dönüş Değeri:**
int - Değerin tüm CollectionBase içinde ilk oluşumunun sıfır tabanlı indeksi, bulunursa; aksi takdirde -1.
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
| index | int | Kaldırılacak bir kategorinin indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondan tüm öğeleri kaldırır.