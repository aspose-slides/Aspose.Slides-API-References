---
title: Presentation
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una presentación de Microsoft PowerPoint.
type: docs
weight: 9320
url: /es/aspose.slides/presentation/
---

## Clase Presentation

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
| [Presentation](presentation#constructor_4)(string) | Este constructor obtiene una ruta de archivo de origen desde la cual se lee el contenido de la presentación. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Este constructor es el mecanismo principal para leer una presentación existente. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Este constructor obtiene una ruta de archivo de origen desde la cual se lee el contenido de la presentación. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Devuelve todas las partes de datos personalizadas en la presentación. Solo lectura [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Devuelve la colección de todos los archivos de audio incrustados en la presentación. Solo lectura [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Devuelve la colección de autores de comentarios. Solo lectura [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Devuelve o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. Por defecto, la hora de creación de este objeto Presentation. Lectura/escritura DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Devuelve los datos personalizados de la presentación. Solo lectura [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Devuelve el estilo de texto predeterminado para las formas. Solo lectura [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Devuelve la colección de firmas utilizadas para firmar la presentación. Solo lectura [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Devuelve el objeto DocumentProperties que contiene propiedades estándar y personalizadas del documento. Solo lectura [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Representa el número de la primera diapositiva en la presentación |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Devuelve el administrador de fuentes. Solo lectura [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Devuelve el administrador de encabezados y pies de página actual. Solo lectura [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Proporciona acceso fácil a todos los hipervínculos contenidos en todas las diapositivas de la presentación (no en la maestra, diseño, notas diapositivas). Solo lectura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Devuelve la colección de todas las imágenes en la presentación. Solo lectura [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Devuelve una lista de todas las diapositivas de diseño que se definen en la presentación. Solo lectura [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Devuelve el administrador de maquetas de handouts. Solo lectura [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Devuelve el administrador de notas maestras. Solo lectura [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Devuelve una lista de todas las diapositivas maestras que se definen en la presentación. Solo lectura [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Devuelve el tema maestro. Solo lectura [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Devuelve el objeto de tamaño de las notas de la diapositiva. Solo lectura [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Obtiene el administrador de permisos para esta presentación. Solo lectura [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Devuelve una lista de todas las secciones de diapositivas que se definen en la presentación. Solo lectura [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Devuelve una lista de todas las diapositivas que se definen en la presentación. Solo lectura [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Devuelve la configuración de la presentación de diapositivas para la presentación. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Devuelve el objeto de tamaño de diapositiva. Solo lectura [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Devuelve información sobre el formato del que se cargó la presentación. Solo lectura [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Obtiene o establece el proyecto VBA con macros de presentación. Lectura/escritura [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Obtiene las propiedades de vista a nivel de presentación. Solo lectura [`IViewProperties`](../iviewproperties). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Libera todos los recursos utilizados por este objeto Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Devuelve objetos de imagen para todas las diapositivas de una presentación. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Devuelve objetos de imagen en miniatura para diapositivas especificadas de una presentación. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Devuelve objetos de imagen en miniatura para todas las diapositivas de una presentación con un tamaño especificado. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Devuelve objetos de imagen en miniatura para todas las diapositivas de una presentación con escalado personalizado. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Devuelve objetos de imagen en miniatura para diapositivas especificadas de una presentación con un tamaño especificado. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Devuelve objetos de imagen en miniatura para diapositivas especificadas de una presentación con escalado personalizado. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Devuelve una diapositiva, diapositiva maestra o diapositiva de diseño por Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Une ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables en todas las diapositivas. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Reemplaza todas las coincidencias de la expresión regular con la cadena especificada. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Reemplaza todas las ocurrencias del texto especificado con otro texto especificado. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan el marcado XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Guarda todas las diapositivas de una presentación en un stream en el formato especificado. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Guarda las diapositivas especificadas de una presentación en un stream en el formato especificado, conservando el número de página. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Guarda todas las diapositivas de una presentación en un stream en el formato especificado y con opciones adicionales. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado, conservando el número de página. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Guarda las diapositivas especificadas de una presentación en un stream en el formato especificado, conservando el número de página. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado, conservando el número de página. |

### Ejemplos

El siguiente ejemplo muestra cómo crear una presentación de PowerPoint.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation presentation = new Presentation())
{
    // Obtener la primera diapositiva
    ISlide slide = presentation.Slides[0];
    // Agregar una forma automática de tipo línea
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Guardar el archivo de presentación.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo abrir y guardar una presentación.

```csharp
[C#]
// Cargar cualquier archivo compatible en Presentation por ejemplo: ppt, pptx, odp etc.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Guardar el archivo de presentación.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Véase también

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->