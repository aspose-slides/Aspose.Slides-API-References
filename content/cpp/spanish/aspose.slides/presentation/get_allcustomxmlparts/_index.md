---
title: get_AllCustomXmlParts()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve todas las partes de datos personalizadas en la presentación. Solo lectura ICustomXmlPart[].
type: docs
weight: 287
url: /es/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() método

Devuelve todas las partes de datos personalizados en la presentación. Solo lectura [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Observaciones

Los siguientes ejemplos muestran cómo eliminar todas las partes xml personalizadas de PowerPoint [Presentation](../).

```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterar todas las partes XML personalizadas
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Ver también

* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [ICustomXmlPart](../../icustomxmlpart/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)