---
title: GetObjectStoringLocation
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina dónde se debe almacenar el objeto. Este método se llama una vez por cada id de objeto. No se garantiza que no habrá dos objetos con el mismo dato, semanticName y contentType pero con un id diferente.
type: docs
weight: 10
url: /es/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---

## ILinkEmbedController.GetObjectStoringLocation método

Determina dónde se debe almacenar el objeto. Este método se llama una vez por cada id de objeto. No se garantiza que no habrá dos objetos con el mismo dato, semanticName y contentType pero con un id diferente.

```csharp
public LinkEmbedDecision GetObjectStoringLocation(int id, byte[] entityData, string semanticName, 
    string contentType, string recomendedExtension)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | Int32 | Id del objeto. Este id es único en toda la operación. |
| entityData | Byte[] | Datos binarios del objeto. Este parámetro puede ser nulo, si los datos binarios del objeto aún no se han generado. |
| semanticName | String | Un texto breve que describe el significado del objeto. El controlador puede usar esto como parte del nombre del objeto externo, pero depende del despachador asegurarse de que los nombres sean únicos y contengan solo caracteres permitidos. |
| contentType | String | Tipo MIME del objeto. |
| recomendedExtension | String | Extensión de nombre de archivo, recomendada para este tipo MIME. |

### Valor de retorno

Decisión

### Véase también

* enum [LinkEmbedDecision](../../linkembeddecision)
* interface [ILinkEmbedController](../../ilinkembedcontroller)
* namespace [Aspose.Slides.Export](../../ilinkembedcontroller)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->