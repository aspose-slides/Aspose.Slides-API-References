---
title: IPresentation
second_title: Referencia de API de Aspose.Slides para .NET
description: Documento de presentación
type: docs
weight: 6550
url: /es/aspose.slides/ipresentation/
---

## Interfaz IPresentation

Documento de presentación

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Devuelve todas las partes de datos personalizadas en la presentación. Solo lectura [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Devuelve la interfaz IDisposable. Solo lectura IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Devuelve la colección de todos los archivos de audio incrustados en la presentación. Solo lectura [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Devuelve la colección de autores de comentarios. Solo lectura [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Devuelve o establece la fecha y hora que sustituirán el contenido de los campos de fecha y hora. Hora de creación de este objeto Presentation por defecto. Lectura/escritura DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Devuelve los datos personalizados de la presentación. Solo lectura [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Devuelve el estilo de texto predeterminado para las formas. Solo lectura [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Devuelve la colección de firmas utilizadas para firmar la presentación. Solo lectura [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Devuelve un objeto DocumentProperties que contiene propiedades del documento estándar y personalizadas. Solo lectura [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Representa el número de la primera diapositiva en la presentación. Lectura/escritura Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Devuelve el administrador de fuentes. Solo lectura [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Devuelve el administrador de encabezados y pies de página de la presentación. Solo lectura [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Proporciona acceso fácil a todos los hiperenlaces contenidos en todas las diapositivas de presentación (no en maestro, diseño, notas de diapositivas). Solo lectura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Devuelve la colección de todas las imágenes en la presentación. Solo lectura [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Devuelve una lista de todas las diapositivas de diseño que están definidas en la presentación. Solo lectura [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Devuelve el administrador de la diapositiva maestra de entrega. Solo lectura [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Devuelve el administrador de notas maestro. Solo lectura [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Devuelve una lista de todas las diapositivas maestras que están definidas en la presentación. Solo lectura [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Devuelve el tema maestro de la presentación. Solo lectura [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Devuelve el objeto de tamaño de diapositiva de notas. Solo lectura [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Obtiene el administrador de permisos para esta presentación. Solo lectura [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Devuelve una lista de todas las secciones de diapositivas que están definidas en la presentación. Solo lectura [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Devuelve una lista de todas las diapositivas que están definidas en la presentación. Solo lectura [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Devuelve el objeto de tamaño de diapositiva. Solo lectura [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Devuelve información sobre el formato desde el cual se cargó la presentación. Solo lectura [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Obtiene el proyecto VBA con macros de presentación. Lectura/escritura [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Obtiene propiedades de visualización a nivel de presentación. Solo lectura [`IViewProperties`](../iviewproperties). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Devuelve un objeto de imagen en miniatura para todas las diapositivas de una presentación. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Devuelve objetos de bitmap en miniatura para diapositivas específicas de una presentación. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Devuelve un objeto de imagen en miniatura para todas las diapositivas de una presentación con tamaño especificado. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Devuelve un objeto de imagen en miniatura para todas las diapositivas de una presentación con escalado personalizado. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Devuelve un objeto de imagen en miniatura para diapositivas específicas de una presentación con tamaño especificado. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Devuelve un objeto de imagen en miniatura para diapositivas específicas de una presentación con escalado personalizado. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Devuelve una Diapositiva, Diapositiva Maestra o Diapositiva de Diseño por Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Une las porciones con el mismo formato en todos los párrafos en todas las formas aceptables en todas las diapositivas. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Reemplaza todas las coincidencias de la expresión regular con la cadena especificada. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Reemplaza todas las ocurrencias del texto especificado con otro texto especificado. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan el marcado XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Guarda todas las diapositivas de una presentación en un flujo en el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Guarda las diapositivas especificadas de una presentación en un flujo en el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Guarda todas las diapositivas de una presentación en un flujo en el formato especificado y con opciones adicionales. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Guarda las diapositivas especificadas de una presentación en un flujo en el formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado. |

### Ver También

* interfaz [IPresentationComponent](../ipresentationcomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->