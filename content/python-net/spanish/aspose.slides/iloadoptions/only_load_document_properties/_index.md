---
title: only_load_document_properties property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties propiedad
Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña.
            El valor true significa que solo las propiedades del documento deben cargarse de un encriptado 
            archivo de presentación y la contraseña debe ser ignorada.
            El valor false significa que toda la presentación encriptada debe cargarse usando la contraseña correcta 
            contraseña.
            Si la presentación no está encriptada, el valor de la propiedad siempre se ignora.
            Si las propiedades del documento de un archivo encriptado no son públicas y el valor de la propiedad es true entonces
            las propiedades del documento no pueden cargarse y se lanzará una excepción.
            Lectura-escritura **bool**.

### Definición:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### Ver también
* clase [`ILoadOptions`](/slides/python-net/es/aspose.slides/iloadoptions)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)