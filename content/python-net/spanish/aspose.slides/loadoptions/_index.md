---
title: LoadOptions class
second_title: Referencia de la API .NET de Aspose.Slides para Python
description: 
type: docs
url: /es/aspose.slides/loadoptions/
---
## LoadOptions clase

Permite especificar opciones adicionales (como formato o fuente predeterminada) al cargar una presentación.

El tipo LoadOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides/loadoptions/__init__/#) | Creates new default load options. |
| [`__init__(self, load_format)`](/slides/python-net/es/aspose.slides/loadoptions/__init__/#loadformat) | Creates new load options. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`load_format`](/slides/python-net/es/aspose.slides/loadoptions/load_format/) | Devuelve o establece el formato de una presentación a cargar.<br/>            Lectura/escritura [`LoadFormat`](/slides/python-net/es/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides/loadoptions/default_regular_font/) | Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente original.<br/>            Lectura/escritura **str**. |
| [`default_symbol_font`](/slides/python-net/es/aspose.slides/loadoptions/default_symbol_font/) | Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente original.<br/>            Lectura/escritura **str**. |
| [`default_asian_font`](/slides/python-net/es/aspose.slides/loadoptions/default_asian_font/) | Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente original.<br/>            Lectura/escritura **str**. |
| [`password`](/slides/python-net/es/aspose.slides/loadoptions/password/) | Obtiene o establece la contraseña.<br/>            Lectura/escritura **str**. |
| [`only_load_document_properties`](/slides/python-net/es/aspose.slides/loadoptions/only_load_document_properties/) | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña.<br/>            Un valor true indica que solo se deben cargar las propiedades del documento desde un archivo de presentación cifrado y se debe ignorar la contraseña.<br/>            Un valor false indica que toda la presentación cifrada debe cargarse utilizando la contraseña correcta.<br/>            Si la presentación no está cifrada, el valor de la propiedad siempre se ignora.<br/>            Si las propiedades del documento de un archivo cifrado no son públicas y el valor de la propiedad es true, entonces las propiedades del documento no pueden cargarse y se lanzará una excepción.<br/>            Lectura/escritura **bool**. |
| [`warning_callback`](/slides/python-net/es/aspose.slides/loadoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/es/aspose.slides/loadoptions/blob_management_options/) | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs),<br/>            como el uso de archivos temporales o el número máximo de bytes de BLOBs en memoria. Estas opciones están destinadas a establecer<br/>            la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares.<br/>            Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad; es decir, un BLOB puede<br/>            ser un audio, video o la propia presentación. |
| [`document_level_font_sources`](/slides/python-net/es/aspose.slides/loadoptions/document_level_font_sources/) | Especifica las fuentes externas que la presentación utilizará.<br/>            Estas fuentes están disponibles para la presentación durante todo su tiempo de vida y no se comparten con otras presentaciones |
| [`interruption_token`](/slides/python-net/es/aspose.slides/loadoptions/interruption_token/) | El token para monitorear solicitudes de interrupción.<br/>            <br/>            Este token gestiona la vida completa de la instancia [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). Cualquier operación de larga duración, como la carga<br/>            o guardado de una presentación, será interrumpida llamando al método [`InterruptionTokenSource.interrupt`](/slides/python-net/es/aspose.slides/interruptiontokensource/interrupt) de<br/>            [`InterruptionTokenSource`](/slides/python-net/es/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/es/aspose.slides/loadoptions/resource_loading_callback/) | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos.<br/>            Lectura/escritura [`IResourceLoadingCallback`](/slides/python-net/es/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/es/aspose.slides/loadoptions/spreadsheet_options/) | Obtiene opciones para hojas de cálculo. Por ejemplo, estas opciones afectan al cálculo de fórmulas para gráficos. |
| [`default_text_language`](/slides/python-net/es/aspose.slides/loadoptions/default_text_language/) | Devuelve o establece el idioma predeterminado para el texto de la presentación.<br/>             Lectura/escritura **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/es/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación.<br/>            <br/>Los tipos de objetos binarios incrustados:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/es/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/es/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lectura/escritura **bool**. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)