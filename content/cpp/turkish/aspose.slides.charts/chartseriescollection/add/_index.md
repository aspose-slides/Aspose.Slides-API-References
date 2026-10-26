---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir grafik serisi oluşturur ve koleksiyona ekler.
type: docs
weight: 53
url: /tr/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) yöntemi

Yeni bir grafik serisi oluşturur ve koleksiyona ekler.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Serinin türü |

### Dönüş Değeri

Yeni grafik serisi.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) yöntemi

[ChartDataCell](../../chartdatacell/) öğesinden yeni bir grafik serisi oluşturur ve koleksiyona ekler.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) serinin adını içeren |
| type | [ChartType](../../charttype/) | Serinin tip ayar türü |

### Dönüş Değeri

Eklenen grafik serisi ya da zaten koleksiyonda bulunan seri.

## Açıklamalar

Eğer aynı hücreden türetilen grafik serisi zaten koleksiyonda ise, yöntem hiçbir şey eklemez ve indeksini döndürür.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) yöntemi

[ChartCellCollection](../../chartcellcollection/) öğesinden yeni bir grafik serisi oluşturur ve koleksiyona ekler.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Serinin adını içeren hücreler |
| type | [ChartType](../../charttype/) | Serinin tip ayar türü |

### Dönüş Değeri

Eklenen grafik serisi ya da zaten koleksiyonda bulunan seri.

## Açıklamalar

Eğer aynı hücreden türetilen grafik serisi zaten koleksiyonda ise, yöntem hiçbir şey eklemez ve indeksini döndürür.

## ChartSeriesCollection::Add(System::String, ChartType) yöntemi

Değerden yeni bir grafik serisi oluşturur ve koleksiyona ekler.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Seri adı. |
| type | [ChartType](../../charttype/) | Serinin tip ayar türü |

### Dönüş Değeri

Eklenen grafik serisi.

## Ayrıca Bakınız

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartSeries](../../ichartseries/)
* Sınıf [ChartSeriesCollection](../)
* Sınıf [IChartDataCell](../../ichartdatacell/)
* Sınıf [IChartCellCollection](../../ichartcellcollection/)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)