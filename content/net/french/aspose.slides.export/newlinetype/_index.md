---
title: NewLineType
second_title: Aspose.Slides pour .NET API Référence
description: Type de nouvelle ligne qui sera utilisée dans le document généré.
type: docs
weight: 4090
url: /fr/aspose.slides.export/newlinetype/
---

## Énumération NewLineType

Type de nouvelle ligne qui sera utilisée dans le document généré.

```csharp
public enum NewLineType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Windows | `0` |  |
| Unix | `1` |  |
| Mac | `2` | Nouvelle ligne Mac (OS 9) - \\r |

### Exemples

Exemple

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

### Voir aussi

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->