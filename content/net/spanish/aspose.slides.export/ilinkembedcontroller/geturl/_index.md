---
title: GetUrl
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve una URL a un objeto externo. Este método siempre se llama si GetObjectStoringLocationaspose.slides.export/ilinkembedcontroller/getobjectstoringlocation devolvió Link y puede ser llamado si GetObjectStoringLocationaspose.slides.export/ilinkembedcontroller/getobjectstoringlocation devolvió Embed, pero la incrustación es imposible. Se puede llamar múltiples veces para el mismo id de objeto.
type: docs
weight: 20
url: /es/aspose.slides.export/ilinkembedcontroller/geturl/
---

## Método ILinkEmbedController.GetUrl

Devuelve una URL a un objeto externo. Este método siempre se llama si [`GetObjectStoringLocation`](../getobjectstoringlocation) devolvió Link y puede ser llamado si [`GetObjectStoringLocation`](../getobjectstoringlocation) devolvió Embed, pero la incrustación es imposible. Se puede llamar múltiples veces para el mismo id de objeto.

```csharp
public string GetUrl(int id, int referrer)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | Int32 | Id del objeto. Este id es único a nivel de operación. |
| referrer | Int32 | Id del objeto de referencia o 0, si el objeto es referenciado por el documento raíz. Puede ser usado para generar un enlace relativo. |

### Valor de Retorno

URL del objeto externo o null si este objeto debe ser ignorado.

### Véase También

* interfaz [ILinkEmbedController](../../ilinkembedcontroller)
* espacio de nombres [Aspose.Slides.Export](../../ilinkembedcontroller)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->