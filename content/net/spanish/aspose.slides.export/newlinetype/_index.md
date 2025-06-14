---
title: NewLineType
second_title: Aspose.Sildes para referencia de API de .NET
description: Tipo de nueva línea que se utilizará en el documento generado.
type: docs
weight: 4090
url: /es/aspose.slides.export/newlinetype/
---

## Enumeración NewLineType

Tipo de nueva línea que se utilizará en el documento generado.

```csharp
public enum NewLineType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Windows | `0` |  |
| Unix | `1` |  |
| Mac | `2` | Nueva línea de Mac (OS 9) - \\r |

### Ejemplos

Ejemplo

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (Stream stream = new FileStream("doc.md", FileMode.OpenOrCreate))
    {
        MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions
        {
            ShowHiddenSlides = true,
            ShowSlideNumber = true,
            Flavor = Flavor.Github,
            ExportType = MarkdownExportType.Sequential,
            NewLineType = NewLineType.Windows
        }
        pres.Save(stream, new[] { 1, 2, 3, 4, 5, 6, 7, 8, 9 }, SaveFormat.Md, markdownSaveOptions);
    }
}
```

### Ver También

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->