---
title: AddSummaryZoomSection()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo objeto Summary Zoom Section y lo agrega a la colección
type: docs
weight: 14
url: /es/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) método

Crea un nuevo objeto Summary Zoom [Section](../../section/) y lo agrega a la colección

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) para un nuevo elemento Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### Valor devuelto

Elemento [ISummaryZoomFrame](../../isummaryzoomframe/) añadido

## Observaciones

Si ya existe un elemento para esta sección en la colección, se devuelve el elemento existente. 

El ejemplo muestra cómo obtener el elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Véase también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [ISummaryZoomSection](../../isummaryzoomsection/)
* Clase [ISection](../../isection/)
* Clase [ISummaryZoomSectionCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)