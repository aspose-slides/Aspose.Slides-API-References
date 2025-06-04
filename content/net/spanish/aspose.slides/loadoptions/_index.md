---
title: LoadOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Permite especificar opciones adicionales como formato o fuente predeterminada al cargar una presentación.
type: docs
weight: 7600
url: /es/aspose.slides/loadoptions/
---

## Clase LoadOptions

Permite especificar opciones adicionales (como formato o fuente predeterminada) al cargar una presentación.

```csharp
public class LoadOptions : ILoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Crea nuevas opciones de carga predeterminadas. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Crea nuevas opciones de carga. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Representa las opciones que se pueden utilizar para gestionar el comportamiento de manejo de objetos grandes binarios (BLOBs), como el uso de archivos temporales o el máximo de bytes de BLOBs en memoria. Estas opciones están destinadas a establecer la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares. Un objeto grande binario (BLOB) es un dato binario almacenado como una sola entidad; es decir, un BLOB puede ser un audio, un video o la presentación en sí. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Devuelve o establece la fuente asiática utilizada en caso de que no se encuentre la fuente fuente. Lectura/escritura String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente regular utilizada en caso de que no se encuentre la fuente fuente. Lectura/escritura String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Devuelve o establece la fuente de símbolo utilizada en caso de que no se encuentre la fuente fuente. Lectura/escritura String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Devuelve o establece el idioma predeterminado para el texto de la presentación. Lectura/escritura String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Especifica las fuentes para las fuentes externas que se utilizarán en la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | El token para monitorear las solicitudes de interrupción. Este token gestiona toda la vida útil de la instancia [`IPresentation`](../ipresentation). Cualquier operación de larga duración, como la carga o el guardado de una presentación, se interrumpirá mediante la llamada al método [`Interrupt`](../interruptiontokensource/interrupt) de [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Devuelve o establece el formato de una presentación a cargar. Lectura/escritura [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Esta propiedad tiene sentido si el archivo de presentación está protegido por contraseña. Un valor verdadero significa que solo se deben cargar las propiedades del documento de un archivo de presentación encriptado y se debe ignorar la contraseña. Un valor falso significa que toda la presentación encriptada debe cargarse utilizando la contraseña correcta. Si la presentación no está encriptada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo encriptado no son públicas y el valor de la propiedad es verdadero, entonces no se pueden cargar las propiedades del documento y se lanzará una excepción. Lectura/escritura Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtiene o establece la contraseña. Lectura/escritura String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. Lectura/escritura [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtiene opciones para hojas de cálculo. Por ejemplo, estas opciones afectan al cálculo de fórmulas para gráficos. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ver También

* interfaz [ILoadOptions](../iloadoptions)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->