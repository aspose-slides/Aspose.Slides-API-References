---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides para Python a través de la referencia de API .NET
description: 
type: docs
url: /es/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded propiedad
Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas.
El valor true significa que solo se cargan las propiedades del documento desde un archivo de presentación encriptado sin usar contraseña.
El valor false significa que se carga toda la presentación encriptada usando la contraseña correcta, no solo se cargan las propiedades del documento.
Si la presentación no está encriptada, entonces el valor de la propiedad es siempre false.
Si las propiedades del documento de un archivo encriptado no son públicas, entonces el valor de la propiedad es siempre false.
Si Presentation.EncryptDocumentProperties es true, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded es siempre false.
Solo lectura **bool**.

### Definición:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Ver también
* clase [`ProtectionManager`](/slides/python-net/es/aspose.slides/protectionmanager)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)