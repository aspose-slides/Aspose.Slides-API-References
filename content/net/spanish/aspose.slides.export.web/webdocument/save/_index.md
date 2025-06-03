---
title: Save
second_title: Referencia de API de Aspose.Slides para .NET
description: Guarda la salida del documento.
type: docs
weight: 50
url: /es/aspose.slides.export.web/webdocument/save/
---

## Método WebDocument.Save

Guarda la salida del documento.

```csharp
public void Save()
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

    // añadir plantilla "index-template.html" con la clave de plantilla "index" para usarla más tarde (para Salida)
    document.Input.AddTemplate<Aspose.Slides.Presentation>("index", "index-template.html");

    // añadir "index.html" a los archivos de salida, utilizando la plantilla "index" para generarlo y la variable pres como modelo
    document.Output.Add("index.html", "index", pres);
    
    // ... configurar otras opciones del documento y luego guardar el documento
    document.Global.Put("slideMargin", 10);
    document.Global.Put("imagesPath", "root/site/images");
    // ...
 
    document.Save();
}
```

### Consulta También

* clase [WebDocument](../../webdocument)
* espacio de nombres [Aspose.Slides.Export.Web](../../webdocument)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->