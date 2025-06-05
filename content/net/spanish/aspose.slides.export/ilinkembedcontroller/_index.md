---
title: ILinkEmbedController
second_title: Referencia de API de Aspose.Slides para .NET
description: Interfaz de callback utilizada para determinar cómo debe procesarse el objeto durante el guardado.
type: docs
weight: 3820
url: /es/aspose.slides.export/ilinkembedcontroller/
---

## Interfaz ILinkEmbedController

Interfaz de callback utilizada para determinar cómo debe procesarse el objeto durante el guardado.

```csharp
public interface ILinkEmbedController
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetObjectStoringLocation](../../aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation)(int, byte[], string, string, string) | Determina dónde debe ser almacenado el objeto. Este método se llama una vez por cada id de objeto. No se garantiza que no haya dos objetos con los mismos datos, semanticName y contentType pero con diferentes id. |
| [GetUrl](../../aspose.slides.export/ilinkembedcontroller/geturl)(int, int) | Devuelve una URL a un objeto externo. Este método se llama siempre si [`GetObjectStoringLocation`](./getobjectstoringlocation) devuelve Link y puede ser llamado si [`GetObjectStoringLocation`](./getobjectstoringlocation) devuelve Embed pero la incrustación es imposible. Puede ser llamado múltiples veces para el mismo id de objeto. |
| [SaveExternal](../../aspose.slides.export/ilinkembedcontroller/saveexternal)(int, byte[]) | Guarda el objeto externo. |

### Véase También

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->