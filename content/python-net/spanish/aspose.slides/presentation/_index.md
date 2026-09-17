---
title: Presentation class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/presentation/
---
## Clase Presentation

Representa una presentación de Microsoft PowerPoint.

El tipo Presentation expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides/presentation/__init__/#) | Este constructor crea una nueva presentación desde cero.<br/>            La presentación creada tiene una diapositiva vacía. |
| [`__init__(self, load_options)`](/slides/python-net/es/aspose.slides/presentation/__init__/#loadoptions) | Este constructor crea una nueva presentación desde cero.<br/>            La presentación creada tiene una diapositiva vacía. |
| [`__init__(self, stream)`](/slides/python-net/es/aspose.slides/presentation/__init__/#iorawiobase) | Este constructor es el mecanismo principal para leer una Presentation existente. |
| [`__init__(self, stream, load_options)`](/slides/python-net/es/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Este constructor es el mecanismo principal para leer una Presentation existente. |
| [`__init__(self, file)`](/slides/python-net/es/aspose.slides/presentation/__init__/#str) | Este constructor obtiene la ruta del archivo fuente del cual<br/>            se leen los contenidos de la Presentation. |
| [`__init__(self, file, load_options)`](/slides/python-net/es/aspose.slides/presentation/__init__/#str-loadoptions) | Este constructor obtiene la ruta del archivo fuente del cual<br/>            se leen los contenidos de la Presentation. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`current_date_time`](/slides/python-net/es/aspose.slides/presentation/current_date_time/) | Devuelve o establece la fecha y hora que sustituirán el contenido de los campos datetime.<br/>            Hora de creación de este objeto Presentation por defecto.<br/>            Lectura/escritura **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/es/aspose.slides/presentation/header_footer_manager/) | Devuelve el administrador actual de HeaderFooter.<br/>            Sólo lectura [`IPresentationHeaderFooterManager`](/slides/python-net/es/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/es/aspose.slides/presentation/protection_manager/) | Obtiene el administrador de permisos para esta presentación.<br/>            Sólo lectura [`IProtectionManager`](/slides/python-net/es/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/es/aspose.slides/presentation/slides/) | Devuelve una lista de todas las diapositivas definidas en la presentación.<br/es/>            Sólo lectura [`ISlideCollection`](/slides/python-net/es/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/es/aspose.slides/presentation/sections/) | Devuelve una lista de todas las secciones de diapositivas definidas en la presentación.<br/>            Sólo lectura [`ISectionCollection`](/slides/python-net/es/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/es/aspose.slides/presentation/slide_size/) | Devuelve el objeto de tamaño de diapositiva.<br/>            Sólo lectura [`ISlideSize`](/slides/python-net/es/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/es/aspose.slides/presentation/notes_size/) | Devuelve el objeto de tamaño de diapositiva de notas.<br/>            Sólo lectura [`INotesSize`](/slides/python-net/es/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/es/aspose.slides/presentation/layout_slides/) | Devuelve una lista de todas las diapositivas de diseño definidas en la presentación.<br/>            Sólo lectura [`IGlobalLayoutSlideCollection`](/slides/python-net/es/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/es/aspose.slides/presentation/masters/) | Devuelve una lista de todas las diapositivas maestras definidas en la presentación.<br/>            Sólo lectura [`IMasterSlideCollection`](/slides/python-net/es/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/es/aspose.slides/presentation/master_notes_slide_manager/) | Devuelve el administrador de notas maestro.<br/>            Sólo lectura [`IMasterNotesSlideManager`](/slides/python-net/es/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/es/aspose.slides/presentation/master_handout_slide_manager/) | Devuelve el administrador de folleto maestro.<br/>            Sólo lectura [`IMasterHandoutSlideManager`](/slides/python-net/es/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/es/aspose.slides/presentation/fonts_manager/) | Devuelve el administrador de fuentes.<br/>            Sólo lectura [`IFontsManager`](/slides/python-net/es/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/es/aspose.slides/presentation/default_text_style/) | Devuelve el estilo de texto predeterminado para las formas.<br/>            Sólo lectura [`ITextStyle`](/slides/python-net/es/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/es/aspose.slides/presentation/comment_authors/) | Devuelve la colección de autores de comentarios.<br/>            Sólo lectura [`ICommentAuthorCollection`](/slides/python-net/es/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/es/aspose.slides/presentation/document_properties/) | Devuelve el objeto DocumentProperties que contiene propiedades de documento estándar y personalizadas.<br/>            Sólo lectura [`IDocumentProperties`](/slides/python-net/es/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/es/aspose.slides/presentation/images/) | Devuelve la colección de todas las imágenes en la presentación.<br/>            Sólo lectura [`IImageCollection`](/slides/python-net/es/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/es/aspose.slides/presentation/audios/) | Devuelve la colección de todos los archivos de audio incrustados en la presentación.<br/>            Sólo lectura [`IAudioCollection`](/slides/python-net/es/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/es/aspose.slides/presentation/videos/) | Devuelve la colección de todos los archivos de video incrustados en la presentación.<br/>            Sólo lectura [`IVideoCollection`](/slides/python-net/es/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/es/aspose.slides/presentation/slide_show_settings/) | Devuelve la configuración de la presentación de diapositivas. |
| [`digital_signatures`](/slides/python-net/es/aspose.slides/presentation/digital_signatures/) | Devuelve la colección de firmas usadas para firmar la presentación.<br/>            Sólo lectura [`IDigitalSignatureCollection`](/slides/python-net/es/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/es/aspose.slides/presentation/custom_data/) | Devuelve los datos personalizados de la presentación.<br/>            Sólo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/es/aspose.slides/presentation/all_custom_xml_parts/) | Devuelve todas las partes de datos personalizados en la presentación.<br/>            Sólo lectura [`ICustomXmlPart`](/slides/python-net/es/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/es/aspose.slides/presentation/vba_project/) | Obtiene o establece el proyecto VBA con macros de la presentación.<br/>            Lectura/escritura [`IVbaProject`](/slides/python-net/es/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/presentation/hyperlink_queries/) | Proporciona acceso fácil a todos los hipervínculos contenidos en todas las diapositivas de la presentación (no en maestras, diseños, diapositivas de notas).<br/>            Sólo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/es/aspose.slides/presentation/view_properties/) | Obtiene las propiedades de vista de toda la presentación.<br/>            Sólo lectura [`IViewProperties`](/slides/python-net/es/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/es/aspose.slides/presentation/first_slide_number/) | Representa el número de la primera diapositiva en la presentación |
| [`sensitivity_labels`](/slides/python-net/es/aspose.slides/presentation/sensitivity_labels/) | Devuelve la colección de etiquetas de sensibilidad aplicadas al documento de la presentación.<br/>            Sólo lectura [`ISensitivityLabelCollection`](/slides/python-net/es/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/es/aspose.slides/presentation/source_format/) | Devuelve información sobre el formato desde el cual se cargó la presentación.<br/>            Sólo lectura [`SourceFormat`](/slides/python-net/es/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/es/aspose.slides/presentation/master_theme/) | Devuelve el tema maestro.<br/>            Sólo lectura [`IMasterTheme`](/slides/python-net/es/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/es/aspose.slides/presentation/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/es/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado. |
| [`save(self, stream, format)`](/slides/python-net/es/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Guarda todas las diapositivas de una presentación en un flujo con el formato especificado. |
| [`save(self, fname, format, options)`](/slides/python-net/es/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/es/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Guarda todas las diapositivas de una presentación en un flujo con el formato especificado y con opciones adicionales. |
| [`save(self, options)`](/slides/python-net/es/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan marcado XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/es/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Guarda diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/es/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Guarda diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página. |
| [`save(self, stream, slides, format)`](/slides/python-net/es/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Guarda diapositivas especificadas de una presentación en un flujo con el formato especificado manteniendo el número de página. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/es/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Guarda diapositivas especificadas de una presentación en un flujo con el formato especificado manteniendo el número de página. |
| [`get_images(self, options)`](/slides/python-net/es/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Devuelve objetos Image para todas las diapositivas de una presentación. |
| [`get_images(self, options, slides)`](/slides/python-net/es/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Devuelve objetos Image en miniatura para diapositivas especificadas de una presentación. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Devuelve objetos Image en miniatura para todas las diapositivas de una presentación con escala personalizada. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Devuelve objetos Image en miniatura para diapositivas especificadas de una presentación con escala personalizada. |
| [`get_images(self, options, image_size)`](/slides/python-net/es/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Devuelve objetos Image en miniatura para todas las diapositivas de una presentación con el tamaño especificado. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/es/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Devuelve objetos Image en miniatura para diapositivas especificadas de una presentación con el tamaño especificado. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/es/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/es/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [`get_slide_by_id(self, id)`](/slides/python-net/es/aspose.slides/presentation/get_slide_by_id/#int) | Devuelve una Slide, MasterSlide o LayoutSlide por Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/presentation/join_portions_with_same_formatting/#) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables en todas las diapositivas. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/es/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/es/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Reemplaza todas las apariciones del texto especificado por otro texto especificado. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/es/aspose.slides/presentation/replace_regex/#str-str) | Reemplaza todas las coincidencias de la expresión regular por la cadena especificada. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)