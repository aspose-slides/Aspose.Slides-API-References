---
title: GetSensitivityLabels()
second_title: Aspose.Slides para la referencia de la API de C++
description: Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /es/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() método


Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Observaciones


El siguiente código muestra cómo mover la información de etiquetas de sensibilidad de las propiedades personalizadas del documento a la colección moderna SensitivityLabels: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Obtenga etiquetas de sensibilidad de las propiedades personalizadas del documento
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Añadir etiqueta a la colección
    // Aquí puede agregar una verificación de la validez de la información de la etiqueta (la etiqueta está disponible, etc.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISensitivityLabel](../../isensitivitylabel/)
* Clase [DocumentProperties](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)