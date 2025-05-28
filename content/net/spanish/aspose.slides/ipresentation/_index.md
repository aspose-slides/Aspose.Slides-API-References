---
title: IPresentation
second_title: Referencia de la API de Aspose.Slides para .NET
description: Documento de presentación
type: docs
weight: 6190
url: /es/aspose.slides/ipresentation/
---
## IPresentation interface

Documento de presentación

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Devuelve todas las partes de datos personalizados en la presentación. Solo lectura[`ICustomXmlPart`](../icustomxmlpart) []. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Devuelve la interfaz IDisposable. Solo lecturaIDisposable . |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPPresentationComponent. Solo lectura[`IPresentationComponent`](../ipresentationcomponent) . |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Devuelve la colección de todos los archivos de audio incrustados en la presentación. Solo lectura[`IAudioCollection`](../iaudiocollection) . |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Devuelve la colección de comentarios autors. Solo lectura[`ICommentAuthorCollection`](../icommentauthorcollection) . |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Devuelve o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. Hora de creación de este objeto de presentación por defecto. Lectura/escrituraDateTime . |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Devuelve los datos personalizados de la presentación. Solo lectura[`ICustomData`](../icustomdata) . |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Devuelve el estilo de texto predeterminado para formas. Solo lectura[`ITextStyle`](../itextstyle) . |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Devuelve la colección de firmas utilizadas para firmar la presentación. Solo lectura[`IDigitalSignatureCollection`](../idigitalsignaturecollection) . |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Devuelve el objeto DocumentProperties que contiene propiedades de documento estándar y personalizadas. Solo lectura[`IDocumentProperties`](../idocumentproperties) . |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Representa el primer número de diapositiva en la presentación. Lectura/escrituraInt32 . |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Devuelve el administrador de fuentes. Solo lectura[`IFontsManager`](../ifontsmanager) . |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Devuelve el administrador de encabezado y pie de página de la presentación. Solo lectura[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Proporciona fácil acceso a todos los hipervínculos contenidos en todas las diapositivas de la presentación (no en las diapositivas maestra, de diseño y de notas). Solo lectura[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Devuelve la colección de todas las imágenes de la presentación. Solo lectura[`IImageCollection`](../iimagecollection) . |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Devuelve una lista de todas las diapositivas de diseño definidas en la presentación. Solo lectura[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) . |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Devuelve el administrador maestro de documentos. Solo lectura[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) . |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Devuelve el administrador maestro de notas. Solo lectura[`IMasterNotesSlideManager`](../imasternotesslidemanager) . |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Devuelve una lista de todas las diapositivas maestras definidas en la presentación. Solo lectura[`IMasterSlideCollection`](../imasterslidecollection) . |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Devuelve el tema maestro de la presentación. Solo lectura[`IMasterTheme`](../../aspose.slides.theme/imastertheme) . |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Devuelve el objeto de tamaño de diapositiva de notas. Solo lectura[`INotesSize`](../inotessize) . |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Obtiene el administrador de los permisos para esta presentación. Solo lectura[`IProtectionManager`](../iprotectionmanager) . |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Devuelve una lista de todas las secciones de diapositivas que están definidas en la presentación. Solo lectura[`ISectionCollection`](../isectioncollection) . |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Devuelve una lista de todas las diapositivas definidas en la presentación. Solo lectura[`ISlideCollection`](../islidecollection) . |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Devuelve el objeto del tamaño de la diapositiva. Solo lectura[`ISlideSize`](../islidesize) . |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Devuelve información sobre desde qué formato se cargó la presentación. Solo lectura[`SourceFormat`](./sourceformat) . |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Obtiene proyecto VBA con macros de presentación. Lectura/escritura[`IVbaProject`](../../aspose.slides.vba/ivbaproject) . |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura[`IVideoCollection`](../ivideocollection) . |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Obtiene las propiedades de vista amplia de la presentación. Solo lectura[`IViewProperties`](../iviewproperties) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Devuelve una diapositiva, MasterSlide o LayoutSlide por Id. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | Devuelve objetos de mapa de bits en miniatura para todas las diapositivas de una presentación. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | Devuelve objetos de mapa de bits en miniatura para diapositivas específicas de una presentación. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | Devuelve objetos de mapa de bits en miniatura para todas las diapositivas de una presentación con el tamaño especificado. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | Devuelve objetos de mapa de bits en miniatura para todas las diapositivas de una presentación con escala personalizada. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | Devuelve objetos de mapa de bits en miniatura para las diapositivas especificadas de una presentación con el tamaño especificado. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | Devuelve objetos de mapa de bits en miniatura para diapositivas específicas de una presentación con escala personalizada. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Une ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables en todas las diapositivas. |
| [Print](../../aspose.slides/ipresentation/print#print)() | Imprime toda la presentación en la impresora predeterminada. |
| [Print](../../aspose.slides/ipresentation/print#print_1)(PrinterSettings) | Imprime la presentación de acuerdo con la configuración de impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario). |
| [Print](../../aspose.slides/ipresentation/print#print_3)(string) | Imprima toda la presentación en la impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario). |
| [Print](../../aspose.slides/ipresentation/print#print_2)(PrinterSettings, string) | Imprime el documento de acuerdo con la configuración de impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de presentación. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan el marcado XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Guarda todas las diapositivas de una presentación en una transmisión en el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Guarda las diapositivas especificadas de una presentación en una transmisión en el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Guarda todas las diapositivas de una presentación en una secuencia en el formato especificado y con opciones adicionales. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Guarda las diapositivas especificadas de una presentación en una transmisión en el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado. |

### Ver también

* interface [IPresentationComponent](../ipresentationcomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
