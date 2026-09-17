---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides para Python a través de la referencia de API .NET
description: 
type: docs
url: /es/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded propiedad
Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas.
El valor true significa que solo se cargan las propiedades del documento desde un archivo de presentación cifrado sin usar la contraseña.
El valor false significa que se carga toda la presentación cifrada usando la contraseña correcta, no solo se cargan las propiedades del documento.
Si la presentación no está cifrada, entonces el valor de la propiedad siempre es false.
Si las propiedades del documento de un archivo cifrado no son públicas, entonces el valor de la propiedad siempre es false.
Si PresentationEx.EncryptDocumentProperties es true, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded siempre es false.
Solo lectura **bool**.

### Definición:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Ver también
* clase [`IProtectionManager`](/slides/python-net/es/aspose.slides/iprotectionmanager)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)