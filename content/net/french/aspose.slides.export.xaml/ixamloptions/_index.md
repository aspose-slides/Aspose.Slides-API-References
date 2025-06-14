---
title: IXamlOptions
second_title: Aspose.Sildes for .NET API Reference
description: Options qui contrôlent comment un document XAML est enregistré.
type: docs
weight: 4510
url: /fr/aspose.slides.export.xaml/ixamloptions/
---

## Interface IXamlOptions

Options qui contrôlent comment un document XAML est enregistré.

```csharp
public interface IXamlOptions : ISaveOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export.xaml/ixamloptions/asisaveoptions) { get; } | Retourne l'interface ISaveOptions. Lecture seule [`ISaveOptions`](../../aspose.slides.export/isaveoptions). |
| [ExportHiddenSlides](../../aspose.slides.export.xaml/ixamloptions/exporthiddenslides) { get; set; } | Détermine si les diapositives cachées seront exportées. |
| [OutputSaver](../../aspose.slides.export.xaml/ixamloptions/outputsaver) { get; set; } | Représente une implémentation de l'interface IOutputSaver. |

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Voir Aussi

* interface [ISaveOptions](../../aspose.slides.export/isaveoptions)
* namespace [Aspose.Slides.Export.Xaml](../../aspose.slides.export.xaml)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->