---
title: Add()
second_title: C++ API Referansı için Aspose.Slides
description: Yeni bir grafik serisi oluşturur ve koleksiyona ekler.
type: docs
weight: 14
url: /tr/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) metodu


Yeni bir grafik serisi oluşturur ve koleksiyona ekler.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Serinin tipi |

### Dönüş Değeri

Yeni grafik serisi.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metodu


[IChartDataCell](../../ichartdatacell/) kaynağından yeni bir grafik serisi oluşturur ve koleksiyona ekler.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) serinin adını içeren. |
| type | [ChartType](../../charttype/) | Seri tipini ayarlayan. |

### Dönüş Değeri

Eklenecek grafik serisi ya da zaten koleksiyonda bulunan seri.

## Açıklamalar


Eğer aynı hücreden oluşturulmuş bir grafik serisi zaten koleksiyonda mevcutsa, yöntem hiçbir şey eklemez ve dizinini döndürür.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metodu


[IChartCellCollection](../../ichartcellcollection/) kaynağından yeni bir grafik serisi oluşturur ve koleksiyona ekler.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Serinin adını içeren hücreler. |
| type | [ChartType](../../charttype/) | Seri tipini ayarlayan. |

### Dönüş Değeri

Eklenecek grafik serisi ya da zaten koleksiyonda bulunan seri.

## Açıklamalar


Eğer aynı hücreden oluşturulmuş bir grafik serisi zaten koleksiyonda mevcutsa, yöntem hiçbir şey eklemez ve dizinini döndürür.



## IChartSeriesCollection::Add(System::String, ChartType) metodu


Değerden yeni bir grafik serisi oluşturur ve koleksiyona ekler.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Seri adı. |
| type | [ChartType](../../charttype/) | Seri tipini ayarlayan. |

### Dönüş Değeri

Eklenecek grafik serisi.



## İlgili

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)