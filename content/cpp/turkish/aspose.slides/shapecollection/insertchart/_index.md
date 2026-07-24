---
title: InsertChart()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler.
type: docs
weight: 92
url: /tr/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metot


Yeni bir grafik oluşturur, örnek seriler ve ayarlarla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Oluşturulacak grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | **float** | Yeni grafiğin genişliği, puan cinsinden. |
| height | **float** | Yeni grafiğin yüksekliği, puan cinsinden. |
| index | **int32_t** | Şekil koleksiyonunda yeni grafiği eklemek için kullanılan sıfır tabanlı dizin. |

### Dönüş Değeri

Yeni oluşturulan [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metot


Yeni bir grafik oluşturur, örnek seriler ve ayarlarla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Oluşturulacak grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | **float** | Yeni grafiğin genişliği, puan cinsinden. |
| height | **float** | Yeni grafiğin yüksekliği, puan cinsinden. |
| index | **int32_t** | Şekil koleksiyonunda yeni grafiği eklemek için kullanılan sıfır tabanlı dizin. |
| initWithSample | **bool** | Yeni grafiği örnek seri verileri ve ayarlarla başlatmak için doğru; serisiz ve sadece minimum ayarlarla grafik oluşturmak için yanlış, bu da oluşturmayı hızlandırır. |

### Dönüş Değeri

Yeni oluşturulan [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Ayrıca Bakınız

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChart](../../../aspose.slides.charts/ichart/)
* Sınıf [ShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)