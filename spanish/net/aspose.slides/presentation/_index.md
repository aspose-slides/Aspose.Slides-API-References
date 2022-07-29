---
title: Presentation
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una presentación de Microsoft PowerPoint.
type: docs
weight: 8870
url: /es/net/aspose.slides/presentation/
---
## Presentation class

Representa una presentación de Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Presentation](presentation#constructor)() | Este constructor crea una nueva presentación desde cero. La presentación creada tiene una diapositiva vacía. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Este constructor crea una nueva presentación desde cero. La presentación creada tiene una diapositiva vacía. |
| [Presentation](presentation#constructor_2)(Stream) | Este constructor es el mecanismo principal para leer una presentación existente. |
| [Presentation](presentation#constructor_4)(string) | Este constructor obtiene una ruta del archivo fuente desde la cual se lee el contenido de la Presentación. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Este constructor es el mecanismo principal para leer una presentación existente. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Este constructor obtiene una ruta del archivo fuente desde la cual se lee el contenido de la Presentación. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Devuelve todas las partes de datos personalizados en la presentación. Solo lectura[`ICustomXmlPart`](../icustomxmlpart) []. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Devuelve la colección de todos los archivos de audio incrustados en la presentación. Solo lectura[`IAudioCollection`](../iaudiocollection) . |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Devuelve la colección de comentarios autors. Solo lectura[`ICommentAuthorCollection`](../icommentauthorcollection) . |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Devuelve o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. Hora de creación de este objeto de presentación por defecto. Lectura/escrituraDateTime . |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Devuelve los datos personalizados de la presentación. Solo lectura[`ICustomData`](../icustomdata) . |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Devuelve el estilo de texto predeterminado para formas. Solo lectura[`ITextStyle`](../itextstyle) . |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Devuelve la colección de firmas utilizadas para firmar la presentación. Solo lectura[`IDigitalSignatureCollection`](../idigitalsignaturecollection) . |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Devuelve el objeto DocumentProperties que contiene propiedades de documento estándar y personalizadas. Solo lectura[`IDocumentProperties`](../idocumentproperties) . |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Representa el primer número de diapositiva en la presentación |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Devuelve el administrador de fuentes. Solo lectura[`IFontsManager`](../ifontsmanager) . |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Devuelve el administrador de encabezado y pie de página real. Solo lectura[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Proporciona fácil acceso a todos los hipervínculos contenidos en todas las diapositivas de la presentación (no en las diapositivas maestra, de diseño y de notas). Solo lectura[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [Images](../../aspose.slides/presentation/images) { get; } | Devuelve la colección de todas las imágenes de la presentación. Solo lectura[`IImageCollection`](../iimagecollection) . |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Devuelve una lista de todas las diapositivas de diseño definidas en la presentación. Solo lectura[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) . |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Devuelve el administrador maestro de documentos. Solo lectura[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) . |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Devuelve el administrador maestro de notas. Solo lectura[`IMasterNotesSlideManager`](../imasternotesslidemanager) . |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Devuelve una lista de todas las diapositivas maestras definidas en la presentación. Solo lectura[`IMasterSlideCollection`](../imasterslidecollection) . |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Devuelve el tema maestro. Solo lectura[`IMasterTheme`](../../aspose.slides.theme/imastertheme) . |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Devuelve el objeto de tamaño de diapositiva de notas. Solo lectura[`INotesSize`](../inotessize) . |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Obtiene el administrador de los permisos para esta presentación. Solo lectura[`IProtectionManager`](../iprotectionmanager) . |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Devuelve una lista de todas las secciones de diapositivas que están definidas en la presentación. Solo lectura[`ISectionCollection`](../isectioncollection) . |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Devuelve una lista de todas las diapositivas definidas en la presentación. Solo lectura[`ISlideCollection`](../islidecollection) . |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Devuelve el objeto del tamaño de la diapositiva. Solo lectura[`ISlideSize`](../islidesize) . |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Devuelve información sobre desde qué formato se cargó la presentación. Solo lectura[`SourceFormat`](../sourceformat) . |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Obtiene o establece un proyecto VBA con macros de presentación. Lectura/escritura[`IVbaProject`](../../aspose.slides.vba/ivbaproject) . |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura[`IVideoCollection`](../ivideocollection) . |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Obtiene las propiedades de vista amplia de la presentación. Solo lectura[`IViewProperties`](../iviewproperties) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Libera todos los recursos usados por este objeto Presentation. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Devuelve una diapositiva, MasterSlide o LayoutSlide por Id. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | Devuelve objetos de mapa de bits en miniatura para todas las diapositivas de una presentación. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | Devuelve objetos de mapa de bits en miniatura para diapositivas específicas de una presentación. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | Devuelve objetos de mapa de bits en miniatura para todas las diapositivas de una presentación con el tamaño especificado. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | Devuelve objetos de mapa de bits en miniatura para todas las diapositivas de una presentación con escala personalizada. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | Devuelve objetos de mapa de bits en miniatura para las diapositivas especificadas de una presentación con el tamaño especificado. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | Devuelve objetos de mapa de bits en miniatura para diapositivas específicas de una presentación con escala personalizada. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Une ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables en todas las diapositivas. |
| [Print](../../aspose.slides/presentation/print#print)() | Imprime toda la presentación en la impresora predeterminada. |
| [Print](../../aspose.slides/presentation/print#print_1)(PrinterSettings) | Imprime la presentación de acuerdo con la configuración de impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario). |
| [Print](../../aspose.slides/presentation/print#print_3)(string) | Imprima toda la presentación en la impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario). |
| [Print](../../aspose.slides/presentation/print#print_2)(PrinterSettings, string) | Imprime el documento de acuerdo con la configuración de impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de presentación. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan el marcado XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Guarda todas las diapositivas de una presentación en una transmisión en el formato especificado. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Guarda las diapositivas especificadas de una presentación en una secuencia en el formato especificado manteniendo el número de página. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Guarda todas las diapositivas de una presentación en una secuencia en el formato especificado y con opciones adicionales. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales. |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Guarda las diapositivas especificadas de una presentación en una secuencia en el formato especificado manteniendo el número de página. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página. |

### Ver también

* interface [IPresentation](../ipresentation)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
