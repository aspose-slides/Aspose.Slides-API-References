---
title: UpdateDocumentProperties()
second_title: Referencia de API de Aspose.Slides para C++
description: Actualiza las propiedades de la presentación vinculada.
type: docs
weight: 92
url: /es/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) método


Actualiza las propiedades de la presentación enlazada.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Observaciones


Este ejemplo muestra cómo llamar al método [PresentationInfo::UpdateDocumentProperties](./) para actualizar las propiedades del documento devueltas por la llamada al método [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/). 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDocumentProperties](../../idocumentproperties/)
* Clase [PresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)