---
title: InsertChart()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarla başlatır ve belirtilen dizindeki şekil koleksiyonuna ekler.
type: docs
weight: 53
url: /tr/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarla başlatır ve belirtilen dizindeki şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Oluşturulacak grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, nokta biriminde. |
| y | **float** | Yeni grafiğin y koordinatı, nokta biriminde. |
| width | **float** | Yeni grafiğin genişliği, nokta biriminde. |
| height | **float** | Yeni grafiğin yüksekliği, nokta biriminde. |
| index | **int32_t** | Yeni grafiği şekil koleksiyonuna eklemek için kullanılan sıfır tabanlı dizin. |

### Dönüş Değeri

Yeni oluşturulan [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarla başlatır ve belirtilen dizindeki şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Oluşturulacak grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, nokta biriminde. |
| y | **float** | Yeni grafiğin y koordinatı, nokta biriminde. |
| width | **float** | Yeni grafiğin genişliği, nokta biriminde. |
| height | **float** | Yeni grafiğin yüksekliği, nokta biriminde. |
| index | **int32_t** | Yeni grafiği şekil koleksiyonuna eklemek için kullanılan sıfır tabanlı dizin. |
| initWithSample | **bool** | Yeni grafiği örnek seri verileri ve ayarlarla başlatmak için true; seri olmadan ve yalnızca minimum ayarlarla grafik oluşturmak (daha hızlı oluşturma sağlar) için false. |

### Dönüş Değeri

Yeni oluşturulan [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Ayrıca Bakınız

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)