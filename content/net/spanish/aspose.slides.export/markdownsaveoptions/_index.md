---
title: MarkdownSaveOptions
second_title: Aspose.Sildes for .NET API Reference
description: Representa opciones que controlan cómo se debe guardar la presentación en markdown.
type: docs
weight: 4080
url: /es/aspose.slides.export/markdownsaveoptions/
---

## MarkdownSaveOptions class

Representa opciones que controlan cómo se debe guardar la presentación en markdown.

```csharp
public class MarkdownSaveOptions : SaveOptions
```

## Constructors

| Nombre | Descripción |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Constructor. |

## Properties

| Nombre | Descripción |
| --- | --- |
| [BasePath](../../aspose.slides.export/markdownsaveoptions/basepath) { get; set; } | Especifica la ruta base donde se guardará el documento con los recursos. El valor predeterminado es el directorio actual de la aplicación. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Cadena de lectura y escritura. |
| [ExportType](../../aspose.slides.export/markdownsaveoptions/exporttype) { get; set; } | Especifica la especificación de markdown para convertir la presentación. El valor predeterminado es `TextOnly`. |
| [Flavor](../../aspose.slides.export/markdownsaveoptions/flavor) { get; set; } | Especifica la especificación de markdown para convertir la presentación. El valor predeterminado es `Multi-markdown`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [HandleRepeatedSpaces](../../aspose.slides.export/markdownsaveoptions/handlerepeatedspaces) { get; set; } |  |
| [ImagesSaveFolderName](../../aspose.slides.export/markdownsaveoptions/imagessavefoldername) { get; set; } | Especifica el nombre de la carpeta para guardar imágenes. El valor predeterminado es `Images`. |
| [NewLineType](../../aspose.slides.export/markdownsaveoptions/newlinetype) { get; set; } | Especifica si el documento generado debe tener nuevas líneas \\r(Macintosh) de \\n(Unix) o \\r\\n(Windows). El valor predeterminado es `Unix`. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RemoveEmptyLines](../../aspose.slides.export/markdownsaveoptions/removeemptylines) { get; set; } | Si se establece en `true`, elimina líneas vacías o solo de espacios en blanco de la salida final en Markdown. El valor predeterminado es `false`. |
| [ShowComments](../../aspose.slides.export/markdownsaveoptions/showcomments) { get; set; } | Especifica si el documento generado debe mostrar comentarios o no. El valor predeterminado es `false`. |
| [ShowHiddenSlides](../../aspose.slides.export/markdownsaveoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [ShowSlideNumber](../../aspose.slides.export/markdownsaveoptions/showslidenumber) { get; set; } | Especifica si el documento generado debe mostrar el número de cada diapositiva o no. El valor predeterminado es `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |
| [SlideNumberFormat](../../aspose.slides.export/markdownsaveoptions/slidenumberformat) { get; set; } | Obtiene o establece la cadena de formato utilizada para los encabezados de números de diapositiva en la salida MD. El formato debe incluir el marcador de posición "{0}", que se reemplazará con el índice de la diapositiva durante la exportación. Ejemplo: "# Diapositiva {0}" producirá "# Diapositiva 1", "# Diapositiva 2", etc. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Examples

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions
    {
        ShowHiddenSlides = true,
        ShowSlideNumber = true,
        Flavor = Flavor.Github,
        ExportType = MarkdownExportType.Sequential,
        NewLineType = NewLineType.Windows
    };
    
    pres.Save("doc.md", new[] { 1, 2, 3, 4, 5, 6, 7, 8, 9 }, SaveFormat.Md, markdownSaveOptions);
}
```

### See Also

* class [SaveOptions](../saveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)