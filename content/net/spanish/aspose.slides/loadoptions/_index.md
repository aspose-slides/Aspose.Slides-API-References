---
title: LoadOptions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Permite especificar opciones adicionales como formato o fuente predeterminada al cargar una presentación.
type: docs
weight: 7140
url: /es/aspose.slides/loadoptions/
---
## LoadOptions class

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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Representa las opciones que se pueden usar para administrar el comportamiento de manejo de objetos binarios grandes (BLOB), como el uso de archivos temporales o el máximo de bytes de BLOB en la memoria. Estas opciones pretendían configurar la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares. Un objeto grande binario (BLOB) es un dato binario almacenado como una sola entidad, es decir, BLOB puede ser un audio, un video o una presentación. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Devuelve o establece la fuente asiática utilizada en caso de que no se encuentre la fuente de origen. Lectura/escrituraString . |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente normal utilizada en caso de que no se encuentre la fuente de origen. Lectura/escrituraString . |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Devuelve o establece la fuente del símbolo utilizada en caso de que no se encuentre la fuente de origen. Lectura/escrituraString . |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Especifica fuentes para las fuentes externas que utilizará la presentación. Estas fuentes están disponibles para la presentación a lo largo de su vida útil y no se comparten con otras presentaciones |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | El token para monitorear las solicitudes de interrupción.  Este token gestiona todo[`IPresentation`](../ipresentation)duración de la instancia. Cualquier operación de larga duración, como cargar o guardar la presentación, se interrumpirá llamando al[`Interrupt`](../interruptiontokensource/interrupt) método de el[`InterruptionTokenSource`](../interruptiontokensource) . |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Devuelve o establece el formato de una presentación para cargar. Lectura/escritura[`LoadFormat`](../loadformat) . |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Esta propiedad tiene sentido, si el archivo de presentación está protegido con contraseña. El valor verdadero significa que solo las propiedades del documento deben cargarse desde un archivo de presentación cifrado y la contraseña debe ignorarse. El valor falso significa que toda la presentación cifrada debe cargarse con uso de la contraseña correcta . Si la presentación no está cifrada, el valor de la propiedad siempre se ignora. Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es verdadero, entonces las propiedades del documento no se pueden cargar y se generará una excepción. Leer escribirBoolean . |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Obtiene o establece la contraseña. Lectura/escrituraString . |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos. Lectura/escritura[`IResourceLoadingCallback`](../iresourceloadingcallback) . |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Obtiene opciones para hojas de cálculo. Por ejemplo, estas opciones afectan el cálculo de fórmulas para gráficos. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se cancelará. Lectura/escritura[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Ver también

* interface [ILoadOptions](../iloadoptions)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
