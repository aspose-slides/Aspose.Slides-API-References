---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni hücreyi koleksiyona ekler.
type: docs
weight: 53
url: /tr/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metodu

Koleksiyona yeni hücre ekler.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Eklenecek yeni hücre. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) metodu

Belirtilen değerden [IChartDataCell](../../ichartdatacell/) oluşturur ve koleksiyona ekler.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Değer. |

## Açıklamalar

Bu metod, AUTO_DATA adlı çalışma sayfasını ekler ve tüm değerleri oraya ekler. [IChartDataWorkbook](../../ichartdataworkbook/) kullanarak [Cell](../../../aspose.slides/cell/) değerlerini ekler veya düzenlerseniz, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu metod kullanılarak eklenen değerlerin maksimum sayısı 16711680'i geçmemelidir.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataCell](../../ichartdatacell/)
* Sınıf [IChartCellCollection](../)
* Sınıf [Object](../../../system/object/)
* İsim Alanı [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)