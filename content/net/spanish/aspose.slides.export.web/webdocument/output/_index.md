---
title: Output
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve la colección de elementos de salida del documento. Solo lectura Outputaspose.slides.export.web/webdocument/output.
type: docs
weight: 40
url: /es/aspose.slides.export.web/webdocument/output/
---

## Propiedad WebDocument.Output

Devuelve la colección de elementos de salida del documento. Solo lectura `Output`.

```csharp
public Output Output { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    var options = new WebDocumentOptions
    {
        TemplateEngine = new RazorTemplateEngine(),
        OutputSaver = new FileOutputSaver(),
        EmbedImages = false
    };
    
    WebDocument document = new WebDocument(options);

    // agregar "index.html" a los archivos de salida, usando la plantilla "index" para generarlo y la variable pres como modelo
    document.Output.Add("index.html", "index", pres);

    // ... configurar otras opciones del documento y luego guardar el documento
    document.Save();
}
```

### Vea También

* class [Output](../../output)
* class [WebDocument](../../webdocument)
* namespace [Aspose.Slides.Export.Web](../../webdocument)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->