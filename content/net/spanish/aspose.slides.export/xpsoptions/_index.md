---
title: XpsOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato XPS.
type: docs
weight: 4540
url: /es/aspose.slides.export/xpsoptions/
---

## Clase XpsOptions

Proporciona opciones que controlan cómo se guarda una presentación en formato XPS.

```csharp
public class XpsOptions : SaveOptions, IXpsOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XpsOptions](xpsoptions)() | Constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente fuente. Lectura-escritura String. |
| [DrawSlidesFrame](../../aspose.slides.export/xpsoptions/drawslidesframe) { get; set; } | Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de callback para actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [SaveMetafilesAsPng](../../aspose.slides.export/xpsoptions/savemetafilesaspng) { get; set; } | Verdadero para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Lectura/escritura Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/xpsoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

El siguiente ejemplo muestra cómo convertir presentaciones a XPS utilizando la configuración predeterminada.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation pres = new Presentation("Convert_XPS.pptx"))
{
    // Guardar la presentación en documento XPS
    pres.Save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
}
```

El siguiente ejemplo muestra cómo convertir presentaciones a XPS utilizando configuraciones personalizadas.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation pres = new Presentation("Convert_XPS_Options.pptx"))
{
    // Instanciar la clase XpsOptions
    XpsOptions options = new XpsOptions();
    // Guardar Metafiles como PNG
    options.SaveMetafilesAsPng = true;
    // Guardar la presentación en documento XPS
    pres.Save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
}
```

### Ver También

* clase [SaveOptions](../saveoptions)
* interfaz [IXpsOptions](../ixpsoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->