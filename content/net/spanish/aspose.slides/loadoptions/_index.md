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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Representa las opciones que se pueden usar para gestionar el comportamiento del manejo de Objetos Binarios Grandes (BLOBs), como el uso de archivos temporales o el máximo de bytes de BLOB en memoria. Estas opciones están diseñadas para establecer la mejor relación entre rendimiento y consumo de memoria para un entorno o requisitos particulares. Un Objeto Binario Grande (BLOB) es un dato binario almacenado como una sola entidad; es decir, un BLOB puede ser un audio, un video o la presentación misma. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Devuelve o establece la fuente asiática utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente regular utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Devuelve o establece la fuente de símbolo utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Devuelve o establece el idioma predeterminado para el texto de la presentación. Lectura/escritura String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Determina si Aspose.Slides eliminará todos los objetos binarios embebidos durante la carga de la presentación. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Especifica las fuentes para fuentes externas que serán utilizadas por la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | El token para monitorear solicitudes de interrupción. Este token gestiona toda la vida útil de la instancia [`IPresentation`](../ipresentation). Cualquier operación de larga duración, como cargar o guardar una presentación, será interrumpida mediante la llamada al método [`Interrupt`](../interruptiontokensource/interrupt) de [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Devuelve o establece el formato de una presentación a cargar. Lectura/escritura [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Esta propiedad tiene sentido si el archivo de presentación está protegido por contraseña. Un valor de verdadero significa que solo se deben cargar las propiedades del documento desde un archivo de presentación cifrado y se debe ignorar la contraseña. Un valor de falso significa que se debe cargar toda la presentación cifrada usando la contraseña correcta. Si la presentación no está cifrada, el valor de la propiedad se ignora siempre. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es verdadero, entonces las propiedades del documento no se pueden cargar y se lanzará una excepción. Lectura/escritura Booleano. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtiene o establece la contraseña. Lectura/escritura String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Devuelve o establece la interfaz de callback que gestiona la carga de recursos externos. Lectura/escritura [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtiene opciones para hojas de cálculo. Por ejemplo, estas opciones afectan el cálculo de fórmulas para gráficos. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ver También

* interfaz [ILoadOptions](../iloadoptions)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->