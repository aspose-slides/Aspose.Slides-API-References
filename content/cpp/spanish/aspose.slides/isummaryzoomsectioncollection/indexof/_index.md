---
title: IndexOf()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el índice del objeto SummaryZoomSection especificado.
type: docs
weight: 53
url: /es/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) método

Devuelve el índice del objeto [SummaryZoomSection](../../summaryzoomsection/) especificado.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objeto para encontrar [ISummaryZoomSection](../../isummaryzoomsection/). |

### Valor de retorno

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
* Clase [ISummaryZoomSectionCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)