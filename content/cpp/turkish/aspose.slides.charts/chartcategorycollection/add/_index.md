---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Eğer kategori koleksiyonda mevcutsa, onu döndürür. Aksi takdirde IChartDataCell'ten yeni bir grafik kategorisi oluşturur ve koleksiyona ekler.
type: docs
weight: 92
url: /tr/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metod


Eğer kategori koleksiyonda mevcutsa, onu döndürür. Aksi takdirde [IChartDataCell](../../ichartdatacell/) kaynağından yeni bir grafik kategorisi oluşturur ve koleksiyona ekler.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) kullanılarak grafik kategorisi oluşturulur. |

### Dönüş Değeri

Eklenen ya da mevcut kategori.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metod


Değerden yeni bir [ChartCategory](../../chartcategory/) oluşturur ve koleksiyona ekler.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Değer. |

### Dönüş Değeri

[IChartCategory](../../ichartcategory/) eklendi.
## Açıklamalar



Bu metod AUTO_DATA adlı çalışma sayfasını ekler ve tüm değerleri oraya ekler. [ChartDataWorkbook](../../chartdataworkbook/) kullanarak hücre değerlerini ekleyip düzenliyorsanız, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu metodla eklenen değerlerin maksimum sayısı 16711680'i geçmemelidir.



## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)