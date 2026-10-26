---
title: IDocumentProperties class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/idocumentproperties/
---
## IDocumentProperties clase

Representa las propiedades de una presentación.

El tipo IDocumentProperties expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`app_version`](/slides/python-net/es/aspose.slides/idocumentproperties/app_version/) | Devuelve la versión de la aplicación.<br/>            Solo lectura **str**. |
| [`name_of_application`](/slides/python-net/es/aspose.slides/idocumentproperties/name_of_application/) | Devuelve o establece el nombre de la aplicación.<br/>            Lectura/escritura **str**. |
| [`company`](/slides/python-net/es/aspose.slides/idocumentproperties/company/) | Devuelve o establece la propiedad de la empresa.<br/>            Lectura/escritura **str**. |
| [`manager`](/slides/python-net/es/aspose.slides/idocumentproperties/manager/) | Devuelve o establece la propiedad del administrador.<br/>            Lectura/escritura **str**. |
| [`presentation_format`](/slides/python-net/es/aspose.slides/idocumentproperties/presentation_format/) | Devuelve o establece el formato previsto de una presentación.<br/>            Lectura/escritura **str**. |
| [`shared_doc`](/slides/python-net/es/aspose.slides/idocumentproperties/shared_doc/) | Determina si la presentación se comparte entre varias personas.<br/>            Lectura/escritura **bool**. |
| [`application_template`](/slides/python-net/es/aspose.slides/idocumentproperties/application_template/) | Devuelve o establece la plantilla de una aplicación.<br/>            Lectura/escritura **str**. |
| [`total_editing_time`](/slides/python-net/es/aspose.slides/idocumentproperties/total_editing_time/) | Tiempo total de edición de una presentación.<br/>            Lectura/escritura **System.TimeSpan**. |
| [`title`](/slides/python-net/es/aspose.slides/idocumentproperties/title/) | Devuelve o establece el título de una presentación.<br/>            Lectura/escritura **str**. |
| [`subject`](/slides/python-net/es/aspose.slides/idocumentproperties/subject/) | Devuelve o establece el asunto de una presentación.<br/>            Lectura/escritura **str**. |
| [`author`](/slides/python-net/es/aspose.slides/idocumentproperties/author/) | Devuelve o establece el autor de una presentación.<br/>            Lectura/escritura **str**. |
| [`keywords`](/slides/python-net/es/aspose.slides/idocumentproperties/keywords/) | Devuelve o establece las palabras clave de una presentación.<br/>            Lectura/escritura **str**. |
| [`comments`](/slides/python-net/es/aspose.slides/idocumentproperties/comments/) | Devuelve o establece los comentarios de una presentación.<br/>            Lectura/escritura **str**. |
| [`category`](/slides/python-net/es/aspose.slides/idocumentproperties/category/) | Devuelve o establece la categoría de una presentación.<br/>            Lectura/escritura **str**. |
| [`created_time`](/slides/python-net/es/aspose.slides/idocumentproperties/created_time/) | Devuelve la fecha en que se creó una presentación. <br/>            Los valores están en UTC.<br/>            Lectura/escritura **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/es/aspose.slides/idocumentproperties/last_saved_time/) | Devuelve la fecha en que se modificó por última vez una presentación.<br/>            Los valores están en UTC.P<br/>            Solo lectura en caso de Presentation.DocumentProperties (porque será actualizado internamente durante el proceso de guardado del objeto IPresentation). <br/>            Puede cambiarse a través de la instancia DocumentProperties devuelta por el método [`IPresentationInfo.read_document_properties`](/slides/python-net/es/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Por favor vea el ejemplo en el resumen del método **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**. |
| [`last_printed`](/slides/python-net/es/aspose.slides/idocumentproperties/last_printed/) | Devuelve o establece la fecha en que una presentación se imprimió por última vez.<br/>            Lectura/escritura **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/es/aspose.slides/idocumentproperties/last_saved_by/) | Devuelve o establece el nombre de la última persona que modificó una presentación.<br/>            Lectura/escritura **str**. |
| [`revision_number`](/slides/python-net/es/aspose.slides/idocumentproperties/revision_number/) | Devuelve o establece el número de revisión de la presentación.<br/>            Lectura/escritura **int**. |
| [`content_status`](/slides/python-net/es/aspose.slides/idocumentproperties/content_status/) | Devuelve o establece el estado del contenido de una presentación.<br/>            Lectura/escritura **str**. |
| [`content_type`](/slides/python-net/es/aspose.slides/idocumentproperties/content_type/) | Devuelve o establece el tipo de contenido de una presentación.<br/>            Lectura/escritura **str**. |
| [`hyperlink_base`](/slides/python-net/es/aspose.slides/idocumentproperties/hyperlink_base/) | Devuelve o establece la propiedad de documento HyperlinkBase.<br/>            Lectura/escritura **str**. |
| [`scale_crop`](/slides/python-net/es/aspose.slides/idocumentproperties/scale_crop/) | Indica el modo de visualización de la miniatura del documento. <br/>            Establezca este elemento a **true** para habilitar el escalado de la miniatura del documento a la pantalla. <br/>            Establezca este elemento a **false** para habilitar el recorte de la miniatura del documento y mostrar solo las secciones que encajen en la pantalla.<br/>            Lectura/escritura **bool**. |
| [`links_up_to_date`](/slides/python-net/es/aspose.slides/idocumentproperties/links_up_to_date/) | Indica si los hipervínculos en un documento están actualizados. <br/>            Establezca este elemento a **true** para indicar que los hipervínculos están actualizados. <br/>            Establezca este elemento a **false** para indicar que los hipervínculos están desactualizados.<br/>            Lectura/escritura **bool**. |
| [`hyperlinks_changed`](/slides/python-net/es/aspose.slides/idocumentproperties/hyperlinks_changed/) | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. <br/>            El siguiente productor que abra este documento deberá actualizar las relaciones de hipervínculos con los nuevos hipervínculos especificados en esta parte.<br/>            Lectura/escritura **bool**. |
| [`slides`](/slides/python-net/es/aspose.slides/idocumentproperties/slides/) | Especifica el número total de diapositivas en un documento de presentación.<br/es/>            Solo lectura **int**. |
| [`hidden_slides`](/slides/python-net/es/aspose.slides/idocumentproperties/hidden_slides/) | Especifica el número de diapositivas ocultas en un documento de presentación.<br/>            Solo lectura **int**. |
| [`notes`](/slides/python-net/es/aspose.slides/idocumentproperties/notes/) | Especifica el número de diapositivas en una presentación que contienen notas.<br/>            Solo lectura **int**. |
| [`paragraphs`](/slides/python-net/es/aspose.slides/idocumentproperties/paragraphs/) | Especifica el número total de párrafos encontrados en un documento, si corresponde.<br/>            Solo lectura **int**. |
| [`words`](/slides/python-net/es/aspose.slides/idocumentproperties/words/) | Especifica el número total de palabras contenidas en un documento.<br/>            Solo lectura **int**. |
| [`multimedia_clips`](/slides/python-net/es/aspose.slides/idocumentproperties/multimedia_clips/) | Especifica el número total de clips de sonido o video que están presentes en el documento.<br/>            Solo lectura **int**. |
| [`titles_of_parts`](/slides/python-net/es/aspose.slides/idocumentproperties/titles_of_parts/) | Especifica el título de cada parte del documento. <br/>            Estas partes no son partes del documento sino representaciones conceptuales de secciones del documento.<br/>            Solo lectura **List[str]**. |
| [`heading_pairs`](/slides/python-net/es/aspose.slides/idocumentproperties/heading_pairs/) | Indica la agrupación de partes del documento y el número de partes en cada grupo.<br/>            Solo lectura **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/es/aspose.slides/idocumentproperties/count_of_custom_properties/) | Devuelve el número de propiedades personalizadas realmente contenidas en una colección.<br/>            Solo lectura **int**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtiene un valor booleano con nombre de las propiedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtiene un valor entero con nombre de las propiedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtiene un valor DateTime con nombre de las propiedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtiene un valor de cadena con nombre de las propiedades personalizadas. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Establece una propiedad personalizada booleana con nombre. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Establece una propiedad personalizada entera con nombre. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Establece una propiedad personalizada DateTime con nombre. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Establece una propiedad personalizada de cadena con nombre. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Establece una propiedad personalizada de tipo float con nombre. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/es/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Establece una propiedad personalizada de tipo double con nombre. |
| [`get_custom_property_name(self, index)`](/slides/python-net/es/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Devuelve el nombre de una propiedad personalizada en el índice especificado. |
| [`remove_custom_property(self, name)`](/slides/python-net/es/aspose.slides/idocumentproperties/remove_custom_property/#str) | Elimina una propiedad personalizada asociada a un nombre especificado. |
| [`contains_custom_property(self, name)`](/slides/python-net/es/aspose.slides/idocumentproperties/contains_custom_property/#str) | Comprueba la presencia de una propiedad personalizada con un nombre especificado. |
| [`clear_custom_properties(self)`](/slides/python-net/es/aspose.slides/idocumentproperties/clear_custom_properties/#) | Elimina todas las propiedades personalizadas. |
| [`clear_built_in_properties(self)`](/slides/python-net/es/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Borra y establece valores predeterminados para todas las propiedades integradas. |
| [`get_sensitivity_labels(self)`](/slides/python-net/es/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Metadatos del SDK de Microsoft Information Protection). |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)