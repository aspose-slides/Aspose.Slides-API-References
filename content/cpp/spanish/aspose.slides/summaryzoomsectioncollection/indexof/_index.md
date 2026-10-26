---
title: IndexOf()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un índice del objeto SummaryZoomSection especificado.
type: docs
weight: 66
url: /es/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) método


Devuelve un índice del objeto [SummaryZoomSection](../../summaryzoomsection/) especificado.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objeto para encontrar [ISummaryZoomSection](../../isummaryzoomsection/). |

### Valor devuelto

Índice de un objeto [SummaryZoomSection](../../summaryzoomsection/) o -1 si el objeto [SummaryZoomSection](../../summaryzoomsection/) no pertenece a esta colección.

## Observaciones



El ejemplo muestra cómo obtener el elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISummaryZoomSection](../../isummaryzoomsection/)
* Clase [SummaryZoomSectionCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)