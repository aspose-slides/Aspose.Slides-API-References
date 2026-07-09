---
title: MarkdownSaveOptions
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa opciones que controlan cómo se debe guardar la presentación en markdown.
type: docs
weight: 4250
url: /es/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions clase

Representa opciones que controlan cómo se debe guardar la presentación en markdown.

```csharp
public class MarkdownSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Ctor. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BasePath](../../aspose.slides.export/markdownsaveoptions/basepath) { get; set; } | Especifica la ruta base donde se guardará el documento con recursos. El valor predeterminado es el directorio actual de la aplicación. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente usada en caso de que no se encuentre la fuente original. Lectura/escritura String. |
| [ExportType](../../aspose.slides.export/markdownsaveoptions/exporttype) { get; set; } | Especifica la especificación markdown para convertir la presentación. El valor predeterminado es `TextOnly`. |
| [Flavor](../../aspose.slides.export/markdownsaveoptions/flavor) { get; set; } | Especifica la especificación markdown para convertir la presentación. El valor predeterminado es `Multi-markdown`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [HandleRepeatedSpaces](../../aspose.slides.export/markdownsaveoptions/handlerepeatedspaces) { get; set; } |  |
| [ImagesSaveFolderName](../../aspose.slides.export/markdownsaveoptions/imagessavefoldername) { get; set; } | Especifica el nombre de la carpeta donde se guardarán las imágenes. El valor predeterminado es `Images`. |
| [NewLineType](../../aspose.slides.export/markdownsaveoptions/newlinetype) { get; set; } | Especifica si el documento generado debe tener nuevas líneas \\r(Macintosh) de \\n(Unix) o \\r\\n(Windows). El valor predeterminado es `Unix`. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RemoveEmptyLines](../../aspose.slides.export/markdownsaveoptions/removeemptylines) { get; set; } | Si se establece en `true`, elimina líneas vacías o que contengan solo espacios en blanco del resultado Markdown final. El valor predeterminado es `false`. |
| [ShowComments](../../aspose.slides.export/markdownsaveoptions/showcomments) { get; set; } | Especifica si el documento generado debe mostrar comentarios o no. El valor predeterminado es `false`. |
| [ShowHiddenSlides](../../aspose.slides.export/markdownsaveoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [ShowSlideNumber](../../aspose.slides.export/markdownsaveoptions/showslidenumber) { get; set; } | Especifica si el documento generado debe mostrar el número de cada diapositiva o no. El valor predeterminado es `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |
| [SlideNumberFormat](../../aspose.slides.export/markdownsaveoptions/slidenumberformat) { get; set; } | Obtiene o establece la cadena de formato utilizada para los encabezados de número de diapositiva en la salida Markdown. El formato debe incluir el marcador \"{0}\", que será reemplazado por el índice de la diapositiva durante la exportación. Ejemplo: \"# Slide {0}\" producirá \"# Slide 1\", \"# Slide 2\", etc. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

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

### Ver también

* clase [SaveOptions](../saveoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->