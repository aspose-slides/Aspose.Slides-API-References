---
title: UpdateDocumentProperties()
second_title: Referencia de API de Aspose.Slides para C++
description: Actualiza las propiedades de la presentación vinculada.
type: docs
weight: 92
url: /es/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) método


Actualiza las propiedades de la presentación vinculada.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Propiedades del documento [IDocumentProperties](../../idocumentproperties/) |
## Observaciones



Este ejemplo muestra cómo llamar al [IPresentationInfo::UpdateDocumentProperties](./) método para actualizar las propiedades del documento devueltas por la llamada al [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) método. 
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
* Clase [IPresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)