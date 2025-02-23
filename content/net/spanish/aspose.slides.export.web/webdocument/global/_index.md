---
title: Global
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve el almacenamiento global del documento. Solo lecturaStorageaspose.slides.export.web/storage .
type: docs
weight: 20
url: /es/aspose.slides.export.web/webdocument/global/
---
## WebDocument.Global property

Devuelve el almacenamiento global del documento. Solo lectura[`Storage`](../../storage) .

```csharp
public Storage Global { get; }
```

### Ejemplos

Usando esto`Global` propiedad (implementación de[`Storage`](../../storage) interfaz) una propiedad se puede usar más adelante en la plantilla:

```csharp
[C#]
var options = new WebDocumentOptions
{
    TemplateEngine = new RazorTemplateEngine(),
    OutputSaver = new FileOutputSaver(),
    EmbedImages = false
};

WebDocument document = new WebDocument(options);

// poner la propiedad "slideMargin" para usar desde las plantillas
document.Global.Put("slideMargin", 10);

// ... configurar otras opciones del documento y luego guardar el documento
document.Save();
```

### Ver también

* class [Storage](../../storage)
* class [WebDocument](../../webdocument)
* espacio de nombres [Aspose.Slides.Export.Web](../../webdocument)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
