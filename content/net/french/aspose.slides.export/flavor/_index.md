---
title: Flavor
second_title: Aspose.Sildes pour .NET API Référence
description: Toutes les spécifications markdown utilisées dans le programme.
type: docs
weight: 3630
url: /fr/aspose.slides.export/flavor/
---

## Énumération Flavor

Toutes les spécifications markdown utilisées dans le programme.

```csharp
public enum Flavor
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Github | `0` | Saveur Github. |
| Gruber | `1` | Saveur Gruber. |
| MultiMarkdown | `2` | Saveur Multi markdown. |
| CommonMark | `3` | Saveur Common mark. |
| MarkdownExtra | `4` | Saveur Markdown extra. |
| Pandoc | `5` | Saveur Pandoc. |
| Kramdown | `6` | Saveur Kramdown. |
| Markua | `7` | Saveur Markua. |
| Maruku | `8` | Saveur Maruku. |
| Markdown2 | `9` | Saveur Markdown2. |
| Remarkable | `10` | Saveur Remarkable. |
| Showdown | `11` | Saveur Showdown. |
| Ghost | `12` | Saveur Ghost. |
| GitLab | `13` | Saveur Gitlab. |
| Haroopad | `14` | Saveur Haroopad. |
| IaWriter | `15` | Saveur IAWriter. |
| Redcarpet | `16` | Saveur Redcarpet. |
| ScholarlyMarkdown | `17` | Saveur Scholarly markdown. |
| Taiga | `18` | Saveur Taiga. |
| Trello | `19` | Saveur Trello. |
| S9ETextFormatter | `20` | Saveur S9E text formatter. |
| XWiki | `21` | Saveur XWiki. |
| StackOverflow | `22` | Saveur Stack overflow. |
| Default | `23` | Saveur markdown par défaut. |

### Exemples

Exemple:

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