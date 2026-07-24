---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyona yeni hücre ekler.
type: docs
weight: 53
url: /tr/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metot

Koleksiyona yeni hücre ekler.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Eklenecek yeni hücre. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) metot

Belirtilen değerden [ChartDataCell](../../chartdatacell/) oluşturur ve koleksiyona ekler.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Değer. |

## Açıklamalar

Bu metot AUTO_DATA adlı çalışma sayfasını ekler ve tüm değerleri oraya ekler. [ChartDataWorkbook](../../chartdataworkbook/) kullanarak [Cell](../../../aspose.slides/cell/) değerlerini eklemek veya düzenlemek isterseniz, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu metotla eklenen değerlerin maksimum sayısı 16711680'i geçmemelidir.

## Başvurular

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataCell](../../ichartdatacell/)
* Sınıf [ChartCellCollection](../)
* Sınıf [Object](../../../system/object/)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)