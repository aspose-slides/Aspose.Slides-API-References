---
title: LoadOptions
second_title: Referencia de API de Aspose.Sildes para .NET
description: Permite especificar opciones adicionales, como formato o fuente predeterminada, al cargar una presentación.
type: docs
weight: 7860
url: /es/aspose.slides/loadoptions/
---
## LoadOptions clase

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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs), como el uso de archivos temporales o el máximo de bytes de BLOBs en memoria. Estas opciones están destinadas a establecer la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares. Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad, es decir, un BLOB puede ser un audio, video o la propia presentación. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Devuelve o establece la fuente asiática utilizada cuando no se encuentra la fuente origen. Lectura/escritura String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente regular utilizada cuando no se encuentra la fuente origen. Lectura/escritura String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Devuelve o establece la fuente símbolo utilizada cuando no se encuentra la fuente origen. Lectura/escritura String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Devuelve o establece el idioma predeterminado para el texto de la presentación. Lectura/escritura String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Especifica las fuentes externas que será utilizada por la presentación. Estas fuentes están disponibles para la presentación durante todo su ciclo de vida y no se comparten con otras presentaciones |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | El token para monitorizar solicitudes de interrupción.  Este token gestiona toda la vida útil de la instancia [`IPresentation`](../ipresentation). Cualquier operación de larga duración, como cargar o guardar una presentación, será interrumpida llamando al método [`Interrupt`](../interruptiontokensource/interrupt) del [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Devuelve o establece el formato de una presentación a cargar. Lectura/escritura [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña. Un valor true indica que solo se deben cargar las propiedades del documento desde un archivo de presentación cifrado y la contraseña debe ser ignorada. Un valor false indica que toda la presentación cifrada debe cargarse usando la contraseña correcta. Si la presentación no está cifrada, entonces el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es true, entonces las propiedades del documento no pueden cargarse y se lanzará una excepción. Lectura/escritura Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtiene o establece la contraseña. Lectura/escritura String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. Lectura/escritura [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtiene opciones para hojas de cálculo. Por ejemplo, estas opciones afectan el cálculo de fórmulas para gráficos. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ver también

* interfaz [ILoadOptions](../iloadoptions)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->