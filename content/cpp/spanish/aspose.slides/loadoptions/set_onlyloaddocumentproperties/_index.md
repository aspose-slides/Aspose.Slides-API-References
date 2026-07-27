---
title: set_OnlyLoadDocumentProperties()
second_title: Referencia de la API de Aspose.Slides para C++
description: Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. El valor true indica que solo se deben cargar las propiedades del documento de un archivo de presentación cifrado y se debe ignorar la contraseña. El valor false indica que toda la presentación cifrada debe cargarse usando la contraseña correcta. Si la presentación no está cifrada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es true, las propiedades del documento no pueden cargarse y se lanzará una excepción. Write bool.
type: docs
weight: 144
url: /es/aspose.slides/loadoptions/set_onlyloaddocumentproperties/
---
## LoadOptions::set_OnlyLoadDocumentProperties(bool) método

Esta propiedad tiene sentido, si el archivo de presentación está protegido con contraseña. El valor true significa que solo se deben cargar las propiedades del documento de un archivo de presentación cifrado y la contraseña debe ignorarse. El valor false significa que toda la presentación cifrada debe cargarse usando la contraseña correcta. Si la presentación no está cifrada, entonces el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es true, entonces las propiedades del documento no pueden cargarse y se lanzará una excepción. Escribe **bool**.

```cpp
void Aspose::Slides::LoadOptions::set_OnlyLoadDocumentProperties(bool value) override
```

## Ver también

* Clase [LoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)