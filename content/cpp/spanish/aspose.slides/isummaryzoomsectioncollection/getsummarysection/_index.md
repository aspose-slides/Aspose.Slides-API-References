---
title: GetSummarySection()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el elemento Summary Zoom Section para la sección dada.
type: docs
weight: 27
url: /es/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) método

Devuelve el elemento Summary Zoom [Section](../../section/) para la sección dada.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) para encontrar [ISection](../../isection/) |

### Valor de retorno

[ISummaryZoomSection](../../isummaryzoomsection/) o null si la colección no contiene elemento para la sección.

## Observaciones

El ejemplo demuestra cómo obtener el elemento Summary Zoom [Section](../../section/) por índice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISummaryZoomSection](../../isummaryzoomsection/)
* Clase [ISection](../../isection/)
* Clase [ISummaryZoomSectionCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)