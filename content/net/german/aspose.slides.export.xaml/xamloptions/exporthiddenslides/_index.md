---
title: ExportHiddenSlides
second_title: Aspose.Slides für .NET-API-Referenz
description: Legt fest ob versteckte Folien exportiert werden.
type: docs
weight: 20
url: /de/aspose.slides.export.xaml/xamloptions/exporthiddenslides/
---
## XamlOptions.ExportHiddenSlides property

Legt fest, ob versteckte Folien exportiert werden.

```csharp
public bool ExportHiddenSlides { get; set; }
```

### Beispiele

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Siehe auch

* class [XamlOptions](../../xamloptions)
* namensraum [Aspose.Slides.Export.Xaml](../../xamloptions)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
