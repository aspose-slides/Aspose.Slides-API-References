---
title: get_OnlyLoadDocumentProperties()
second_title: Referencia de API de Aspose.Slides para C++
description: Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor true significa que solo se deben cargar las propiedades del documento desde un archivo de presentación cifrado y la contraseña debe ser ignorada. Un valor false significa que toda la presentación cifrada debe cargarse utilizando la contraseña correcta. Si la presentación no está cifrada, entonces el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es true, entonces las propiedades del documento no pueden cargarse y se lanzará una excepción. Lee bool.
type: docs
weight: 131
url: /es/aspose.slides/iloadoptions/get_onlyloaddocumentproperties/
---
## ILoadOptions::get_OnlyLoadDocumentProperties() método

Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor true indica que solo se deben cargar las propiedades del documento desde un archivo de presentación cifrado y se debe ignorar la contraseña. Un valor false indica que se debe cargar la presentación completa cifrada usando la contraseña correcta. Si la presentación no está cifrada, entonces el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es true, entonces no se pueden cargar las propiedades del documento y se lanzará una excepción. Lee **bool**.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_OnlyLoadDocumentProperties()=0
```

## Ver también

* Clase [ILoadOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)