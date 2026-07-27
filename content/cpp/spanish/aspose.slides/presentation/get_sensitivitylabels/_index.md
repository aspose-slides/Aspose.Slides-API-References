---
title: get_SensitivityLabels()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la colección de etiquetas de sensibilidad aplicadas al documento de la presentación. Solo lectura ISensitivityLabelCollection.
type: docs
weight: 378
url: /es/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() método


Devuelve la colección de etiquetas de sensibilidad aplicadas al documento de la presentación. Solo lectura [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Comentarios



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Imprime las etiquetas aplicadas
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Agrega la nueva etiqueta
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Obtiene el Id de la etiqueta de sensibilidad de la política
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Obtiene el identificador del sitio Azure AD de la política
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)