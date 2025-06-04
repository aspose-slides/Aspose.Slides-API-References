---
title: Global
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve el almacenamiento global del documento. Solo lectura Storageaspose.slides.export.web/storage.
type: docs
weight: 20
url: /es/aspose.slides.export.web/webdocument/global/
---

## Propiedad WebDocument.Global

Devuelve el almacenamiento global del documento. Solo lectura [`Storage`](../../storage).

```csharp
public Storage Global { get; }
```

### Ejemplos

Usando esta propiedad `Global` (implementación de la interfaz [`Storage`](../../storage)) se puede utilizar una propiedad para usarla más tarde en la plantilla:

```csharp
[C#]
var options = new WebDocumentOptions
{
    TemplateEngine = new RazorTemplateEngine(),
    OutputSaver = new FileOutputSaver(),
    EmbedImages = false
};

WebDocument document = new WebDocument(options);

// poner la propiedad "slideMargin" en uso desde plantillas
document.Global.Put("slideMargin", 10);

// ... configurar otras opciones del documento y luego guardar el documento
document.Save();
```

### Véase También

* class [Storage](../../storage)
* class [WebDocument](../../webdocument)
* namespace [Aspose.Slides.Export.Web](../../webdocument)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->