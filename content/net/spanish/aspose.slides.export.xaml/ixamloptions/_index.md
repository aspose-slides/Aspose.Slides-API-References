---
title: IXamlOptions
second_title: Aspose.Slides para .NET Referencia de API
description: Opciones que controlan cómo se guarda un documento XAML.
type: docs
weight: 4510
url: /es/aspose.slides.export.xaml/ixamloptions/
---

## Interfaz IXamlOptions

Opciones que controlan cómo se guarda un documento XAML.

```csharp
public interface IXamlOptions : ISaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export.xaml/ixamloptions/asisaveoptions) { get; } | Devuelve la interfaz ISaveOptions. Solo lectura [`ISaveOptions`](../../aspose.slides.export/isaveoptions). |
| [ExportHiddenSlides](../../aspose.slides.export.xaml/ixamloptions/exporthiddenslides) { get; set; } | Determina si las diapositivas ocultas serán exportadas. |
| [OutputSaver](../../aspose.slides.export.xaml/ixamloptions/outputsaver) { get; set; } | Representa una implementación de la interfaz IOutputSaver. |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Ver También

* interfaz [ISaveOptions](../../aspose.slides.export/isaveoptions)
* espacio de nombres [Aspose.Slides.Export.Xaml](../../aspose.slides.export.xaml)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->