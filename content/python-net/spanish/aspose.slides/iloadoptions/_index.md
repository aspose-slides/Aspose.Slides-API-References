---
title: ILoadOptions class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iloadoptions/
---
## ILoadOptions clase

Permite especificar opciones adicionales (como formato o fuente predeterminada) al cargar una presentación.

El tipo ILoadOptions expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`load_format`](/slides/python-net/es/aspose.slides/iloadoptions/load_format/) | Devuelve o establece el formato de una presentación a cargar.<br/>            Lectura/escritura [`LoadFormat`](/slides/python-net/es/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/es/aspose.slides/iloadoptions/default_regular_font/) | Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente original.<br/>            Lectura-escritura **str**. |
| [`default_symbol_font`](/slides/python-net/es/aspose.slides/iloadoptions/default_symbol_font/) | Devuelve o establece la fuente Symbol utilizada en caso de que no se encuentre la fuente original.<br/>            Lectura-escritura **str**. |
| [`default_asian_font`](/slides/python-net/es/aspose.slides/iloadoptions/default_asian_font/) | Devuelve o establece la fuente Asian utilizada en caso de que no se encuentre la fuente original.<br/>            Lectura-escritura **str**. |
| [`password`](/slides/python-net/es/aspose.slides/iloadoptions/password/) | Obtiene o establece la contraseña.<br/>            Lectura-escritura **str**. |
| [`only_load_document_properties`](/slides/python-net/es/aspose.slides/iloadoptions/only_load_document_properties/) | Esta propiedad tiene sentido si el archivo de la presentación está protegido con contraseña.<br/>            Un valor true indica que solo se deben cargar las propiedades del documento desde un archivo de presentación encriptado y la contraseña debe ser ignorada.<br/>            Un valor false indica que toda la presentación encriptada debe cargarse utilizando la contraseña correcta.<br/>            Si la presentación no está encriptada, entonces el valor de la propiedad siempre se ignora.<br/>            Si las propiedades del documento de un archivo encriptado no son públicas y el valor de la propiedad es true, entonces las propiedades del documento no pueden cargarse y se lanzará una excepción.<br/>            Lectura-escritura **bool**. |
| [`warning_callback`](/slides/python-net/es/aspose.slides/iloadoptions/warning_callback/) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará.<br/>            Lectura/escritura [`IWarningCallback`](/slides/python-net/es/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/es/aspose.slides/iloadoptions/blob_management_options/) | Representa las opciones que pueden usarse para gestionar el comportamiento de manejo de Binary Large Objects (BLOBs),<br/>            como el uso de archivos temporales o la cantidad máxima de bytes de BLOBs en memoria. Estas opciones están destinadas a configurar<br/>            la mejor relación rendimiento/consumo de memoria para un entorno o requisitos particulares.<br/>            Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad; por ejemplo, un BLOB puede <br/>            ser un audio, video o la propia presentación. |
| [`document_level_font_sources`](/slides/python-net/es/aspose.slides/iloadoptions/document_level_font_sources/) | Especifica las fuentes externas que se utilizarán en la presentación.<br/>            Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones. |
| [`interruption_token`](/slides/python-net/es/aspose.slides/iloadoptions/interruption_token/) | El token para monitorizar solicitudes de interrupción.<br/>            <br/>            Este token gestiona toda la vida útil de la instancia [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). Cualquier operación de larga duración, como la carga o guardado de una presentación, será interrumpida llamando al método [`IInterruptionTokenSource.interrupt`](/slides/python-net/es/aspose.slides/iinterruptiontokensource/interrupt) del [`IInterruptionTokenSource`](/slides/python-net/es/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/es/aspose.slides/iloadoptions/resource_loading_callback/) | Devuelve o establece la interfaz de devolución de llamada que gestiona la carga de recursos externos.<br/>            Lectura/escritura [`IResourceLoadingCallback`](/slides/python-net/es/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/es/aspose.slides/iloadoptions/spreadsheet_options/) | Representa las opciones que pueden usarse para especificar el comportamiento adicional de las hojas de cálculo. |
| [`default_text_language`](/slides/python-net/es/aspose.slides/iloadoptions/default_text_language/) | Devuelve o establece el idioma predeterminado para el texto de la presentación.<br/>             Lectura/escritura **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/es/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Determina si Aspose.Slides eliminará todos los objetos binarios incrustados durante la carga de la presentación.<br/>            <br/>Los tipos de objetos binarios incrustados:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/es/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/es/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lectura/escritura **bool**. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)