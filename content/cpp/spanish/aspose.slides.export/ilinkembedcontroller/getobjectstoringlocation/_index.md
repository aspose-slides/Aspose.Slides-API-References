---
title: GetObjectStoringLocation()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina dónde debe almacenarse el objeto. Este método se llama una vez por cada id de objeto. No se garantiza que no haya dos objetos con los mismos datos, semanticName y contentType pero con diferentes id.
type: docs
weight: 1
url: /es/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) método

Determina dónde debe almacenarse el objeto. Este método se llama una vez por cada id de objeto. No se garantiza que no haya dos objetos con los mismos datos, semanticName y contentType pero con diferentes id.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | **int32_t** | Id del objeto. Este id es único en toda la operación de guardado. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datos binarios del objeto. Este parámetro puede ser nulo, si los datos binarios del objeto aún no se han generado. |
| semanticName | [System::String](../../../system/string/) | Algún texto corto que describa el significado del objeto. El controlador puede usarlo como parte del nombre externo del objeto, pero corresponde al despachador garantizar que los nombres sean únicos y contengan solo caracteres permitidos. |
| contentType | [System::String](../../../system/string/) | Tipo MIME del objeto. |
| recomendedExtension | [System::String](../../../system/string/) | Extensión de nombre de archivo, recomendada para este tipo MIME. |

### Valor de retorno

Decisión

## Ver también

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)