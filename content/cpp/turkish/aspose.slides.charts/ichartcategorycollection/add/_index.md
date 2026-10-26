---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Kategori koleksiyonda mevcutsa, onu döndürür. Aksi takdirde IChartDataCell'ten yeni bir grafik kategorisi oluşturur ve koleksiyona ekler.
type: docs
weight: 53
url: /tr/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) method


Eğer kategori koleksiyonda mevcutsa, onu döndürür. Aksi takdirde [IChartDataCell](../../ichartdatacell/)'den yeni bir grafik kategorisi oluşturur ve koleksiyona ekler.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) kullanılarak grafik kategorisi oluşturulur. |

### Dönüş Değeri

Eklenen veya mevcut kategori.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) method


Değerden yeni bir [IChartCategory](../../ichartcategory/) oluşturur ve koleksiyona ekler.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Değer. |

### Dönüş Değeri

Eklenen [IChartCategory](../../ichartcategory/).
## Açıklamalar



Bu yöntem AUTO_DATA adlı çalışma sayfasını ekler ve tüm değerleri oraya ekler. [IChartDataWorkbook](../../ichartdataworkbook/)'yi hücre değerlerini eklemek veya düzenlemek için kullanıyorsanız, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i geçmemelidir.



## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartCategory](../../ichartcategory/)
* Sınıf [IChartDataCell](../../ichartdatacell/)
* Sınıf [IChartCategoryCollection](../)
* Sınıf [Object](../../../system/object/)
* İsim Uzayı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)