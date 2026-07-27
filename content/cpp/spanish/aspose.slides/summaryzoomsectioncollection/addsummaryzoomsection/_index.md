---
title: AddSummaryZoomSection()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo objeto Summary Zoom Section y lo añade a la colección
type: docs
weight: 53
url: /es/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) método


Crea un nuevo objeto Summary Zoom [Section](../../section/) y lo añade a la colección

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) para un nuevo Summary Zoom [Section](../../section/) elemento [ISection](../../isection/) |

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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)