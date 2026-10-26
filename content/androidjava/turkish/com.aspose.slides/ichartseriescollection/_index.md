---
title: IChartSeriesCollection
second_title: Java API Referansı ile Android için Aspose.Slides
description: Koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/ichartseriescollection/
---
**Tüm Gerçekleştirilen Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

[IChartSeries](../../com.aspose.slides/ichartseries) koleksiyonunu temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [add(int type)](#add-int-) | Yeni bir grafik serisi oluşturur ve koleksiyona ekler. |
| [insert(int index, int type)](#insert-int-int-) | Yeni bir grafik serisi oluşturur ve koleksiyona yerleştirir. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Yeni bir grafik serisini [IChartDataCell](../../com.aspose.slides/ichartdatacell) kaynağından oluşturur ve koleksiyona ekler. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Yeni bir grafik serisini [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) kaynağından oluşturur ve koleksiyona ekler. |
| [add(String name, int type)](#add-java.lang.String-int-) | Değerden yeni bir grafik serisi oluşturur ve koleksiyona ekler. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Belirtilen [IChartSeries](../../com.aspose.slides/ichartseries)'yi arar ve tüm Collection içinde ilk gerçekleşmenin sıfır tabanlı indeksini döndürür. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Belirtilen değeri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki öğeyi kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri (grafik stilini de dahil) kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Belirtilen indeksteki öğe.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Yeni bir grafik serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Serinin tipi |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Yeni grafik serisi.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Yeni bir grafik serisi oluşturur ve koleksiyona yerleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ekleme için indeks |
| type | int | Grafik tipi [ChartType](../../com.aspose.slides/charttype) |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Yeni grafik serisi [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

[IChartDataCell](../../com.aspose.slides/ichartdatacell) kaynağından yeni bir grafik serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Seri adını içeren hücre. |
| type | int | Seri tipini ayarlar

--------------------

Aynı hücreden oluşturulan grafik serisi zaten koleksiyonda varsa yöntem hiçbir şey eklemez ve indeksini döndürür. |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen grafik serisi veya zaten koleksiyonda olan seri.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) kaynağından yeni bir grafik serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Seri adını içeren hücreler. |
| type | int | Seri tipini ayarlar

--------------------

Aynı hücreden oluşturulan grafik serisi zaten koleksiyonda varsa yöntem hiçbir şey eklemez ve indeksini döndürür. |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen grafik serisi veya zaten koleksiyonda olan seri.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Değerden yeni bir grafik serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Seri adı. |
| type | int | Seri tipini ayarlar |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen grafik serisi.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Belirtilen [IChartSeries](../../com.aspose.slides/ichartseries)'yi arar ve tüm Collection içinde ilk gerçekleşmenin sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Grafik serisi değeri. |

**Döndürür:**
int - Değerin tüm CollectionBase içinde ilk gerçekleşmesinin sıfır tabanlı indeksi, bulunursa; aksi takdirde -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Belirtilen değeri kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Değer. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks |

### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm öğeleri (grafik stilini de dahil) kaldırır.