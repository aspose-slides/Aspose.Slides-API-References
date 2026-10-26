---
title: Remove()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina el elemento de la colección.
type: docs
weight: 79
url: /es/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) método


Elimina el elemento de la colección.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Punto de datos a eliminar. |

### Valor devuelto

true si el elemento se elimina correctamente; de lo contrario, false. Este método también devuelve false si el elemento no se encontró en el [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) método


Elimina el elemento de la colección mediante su índice en la colección de puntos de la serie principal.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Índice del punto de datos en la colección de puntos de la serie principal. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartDataPoint](../../ichartdatapoint/)
* Clase [PieSplitCustomPointCollection](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)