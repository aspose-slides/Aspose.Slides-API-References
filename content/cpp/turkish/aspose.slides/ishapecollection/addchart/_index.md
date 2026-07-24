---
title: AddChart()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 27
url: /tr/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metodu


Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Eklenecek grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, nokta cinsinden. |
| width | **float** | Grafiğin genişliği, nokta cinsinden. |
| height | **float** | Grafiğin yüksekliği, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metodu


Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Eklenecek grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, nokta cinsinden. |
| width | **float** | Grafiğin genişliği, nokta cinsinden. |
| height | **float** | Grafiğin yüksekliği, nokta cinsinden. |
| initWithSample | **bool** | Yeni grafiği örnek seri verileri ve ayarlarla başlatmak için true; serisiz ve yalnızca temel ayarlarla oluşturmak, böylece oluşturma daha hızlı olur, için false. |

### Dönüş Değeri

Yeni oluşturulan [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Ayrıca Bakınız

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)