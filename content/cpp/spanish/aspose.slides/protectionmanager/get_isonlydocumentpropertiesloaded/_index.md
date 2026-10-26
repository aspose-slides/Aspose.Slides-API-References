---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Referencia de API de Aspose.Slides para C++
description: Esta propiedad tiene sentido si el archivo de presentación está protegido por contraseña y las propiedades del documento de este archivo son públicas. Un valor de true indica que solo se cargan las propiedades del documento desde un archivo de presentación cifrado sin usar la contraseña. Un valor de false indica que se carga toda la presentación cifrada utilizando la contraseña correcta, no solo se cargan las propiedades del documento. Si la presentación no está cifrada, el valor de la propiedad es siempre false. Si las propiedades del documento de un archivo cifrado no son públicas, el valor de la propiedad es siempre false. Si Presentation.EncryptDocumentProperties es true, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded es siempre false. Solo lectura bool.
type: docs
weight: 40
url: /es/aspose.slides/protectionmanager/get_isonlydocumentpropertiesloaded/
---
## ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() método

Esta propiedad tiene sentido si el archivo de presentación está protegido por contraseña y las propiedades del documento de este archivo son públicas. Un valor de true significa que solo se cargan las propiedades del documento desde un archivo de presentación cifrado sin usar la contraseña. Un valor de false significa que se carga toda la presentación cifrada utilizando la contraseña correcta, no solo se cargan las propiedades del documento. Si la presentación no está cifrada, el valor de la propiedad es siempre false. Si las propiedades del documento de un archivo cifrado no son públicas, el valor de la propiedad es siempre false. Si Presentation.EncryptDocumentProperties es true, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded es siempre false. Solo lectura **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() override
```

## Ver también

* Clase [ProtectionManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)