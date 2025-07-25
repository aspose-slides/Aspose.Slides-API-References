---
title: Save
second_title: Aspose.Slides für .NET API-Referenz
description: Speichert die Dokumentenausgabe.
type: docs
weight: 50
url: /de/aspose.slides.export.web/webdocument/save/
---

## WebDocument.Save Methode

Speichert die Dokumentenausgabe.

```csharp
public void Save()
```

### Beispiele

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

    // Fügen Sie die "index-template.html" Vorlage mit dem "index" Vorlagenschlüssel hinzu, um sie später (für die Ausgabe) zu verwenden
    document.Input.AddTemplate<Aspose.Slides.Presentation>("index", "index-template.html");

    // Fügen Sie "index.html" zu den Ausgabedateien hinzu, verwenden Sie die "index" Vorlage, um es zu generieren, und die pres-Variable als Modell
    document.Output.Add("index.html", "index", pres);
    
    // ... richten Sie andere Optionen des Dokuments ein und speichern Sie dann das Dokument
    document.Global.Put("slideMargin", 10);
    document.Global.Put("imagesPath", "root/site/images");
    // ...
 
    document.Save();
}
```

### Siehe auch

* Klasse [WebDocument](../../webdocument)
* Namespace [Aspose.Slides.Export.Web](../../webdocument)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->