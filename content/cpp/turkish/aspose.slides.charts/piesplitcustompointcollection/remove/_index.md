---
title: Remove()
second_title: Aspose.Slides için C++ API Referansı
description: Koleksiyondan öğeyi kaldırır.
type: docs
weight: 79
url: /tr/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) yöntemi


Koleksiyondan öğeyi kaldırır.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Kaldırılacak veri noktası. |

### Dönüş Değeri

öğe başarılı bir şekilde kaldırıldıysa true; aksi takdirde false. [System::Collections::Generic::List](../../../system.collections.generic/list/){T} içinde öğe bulunamazsa bu yöntem ayrıca false döndürür.

## PieSplitCustomPointCollection::Remove(int32_t) yöntemi


Koleksiyondan öğeyi, üst serinin nokta koleksiyonundaki indeksine göre kaldırır.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Üst serinin nokta koleksiyonundaki veri noktasının indeksi. |

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataPoint](../../ichartdatapoint/)
* Sınıf [PieSplitCustomPointCollection](../)
* İsim Uzayı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)