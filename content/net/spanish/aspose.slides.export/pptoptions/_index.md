---
title: PptOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato PPT.
type: docs
weight: 4170
url: /es/aspose.slides.export/pptoptions/
---

## Clase PptOptions

Proporciona opciones que controlan cómo se guarda una presentación en formato PPT.

```csharp
public class PptOptions : SaveOptions, IPptOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PptOptions](pptoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Lectura y escritura String. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de callback para guardar las actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RootDirectoryClsid](../../aspose.slides.export/pptoptions/rootdirectoryclsid) { get; set; } | Representa el GUID de clase de objeto (CLSID) que se almacena en la entrada del directorio raíz. Se puede usar para la activación COM de la aplicación del documento. El valor predeterminado es '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hiperenlaces con llamadas a JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Véase También

* clase [SaveOptions](../saveoptions)
* interfaz [IPptOptions](../ipptoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->