---
title: ILoadOptions
second_title: Aspose.Slides para .NET API Referencia
description: Permite especificar opciones adicionales como formato o fuente predeterminada al cargar una presentación.
type: docs
weight: 6140
url: /es/aspose.slides/iloadoptions/
---

## Interfaz ILoadOptions

Permite especificar opciones adicionales (como formato o fuente predeterminada) al cargar una presentación.

```csharp
public interface ILoadOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Representa las opciones que se pueden utilizar para gestionar el comportamiento del manejo de Objetos Grandes Binarios (BLOBs), como el uso de archivos temporales o el máximo de bytes de BLOBs en memoria. Estas opciones están destinadas a establecer la mejor relación entre rendimiento y consumo de memoria para un entorno o requisitos particulares. Un Objeto Grande Binario (BLOB) es un dato binario almacenado como una única entidad - es decir, un BLOB puede ser un audio, video o la propia presentación. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Devuelve o establece la fuente asiática utilizada en caso de que no se encuentre la fuente de origen. String de lectura y escritura. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente regular utilizada en caso de que no se encuentre la fuente de origen. String de lectura y escritura. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Devuelve o establece la fuente de símbolo utilizada en caso de que no se encuentre la fuente de origen. String de lectura y escritura. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Devuelve o establece el idioma predeterminado para el texto de la presentación. String de lectura y escritura. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Especifica las fuentes para fuentes externas que serán utilizadas por la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | El token para monitorear las solicitudes de interrupción. Este token gestiona toda la vida útil de la instancia [`IPresentation`](../ipresentation). Cualquier operación de larga duración, como la carga o el guardado de presentaciones, se interrumpirá mediante la llamada al método [`Interrupt`](../iinterruptiontokensource/interrupt) de [`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Devuelve o establece el formato de una presentación a cargar. Lectura/escritura [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Esta propiedad tiene sentido si el archivo de presentación está protegido por contraseña. Un valor de verdadero significa que solo deben cargarse las propiedades del documento de un archivo de presentación cifrado y se debe ignorar la contraseña. Un valor de falso significa que toda la presentación cifrada debe ser cargada con el uso de la contraseña correcta. Si la presentación no está cifrada, entonces el valor de la propiedad se ignora siempre. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es verdadero, entonces no se pueden cargar las propiedades del documento y se lanzará una excepción. Booleano de lectura y escritura. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Obtiene o establece la contraseña. String de lectura y escritura. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. Lectura/escritura [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Representa opciones que se pueden utilizar para especificar el comportamiento adicional de hojas de cálculo. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ver También

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->