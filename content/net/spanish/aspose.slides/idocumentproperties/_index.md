---
title: IDocumentProperties
second_title: Referencia de la API de Aspose.Sildes para .NET
description: Representa las propiedades de una presentación.
type: docs
weight: 5710
url: /es/aspose.slides/idocumentproperties/
---
## IDocumentProperties interfaz

Representa las propiedades de una presentación.

```csharp
public interface IDocumentProperties
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Devuelve o establece la plantilla de una aplicación. Lectura/escritura String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Devuelve la versión de la aplicación. Solo lectura String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Devuelve o establece el autor de una presentación. Lectura/escritura String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Devuelve o establece la categoría de una presentación. Lectura/escritura String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Devuelve o establece los comentarios de una presentación. Lectura/escritura String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Devuelve o establece la propiedad de la compañía. Lectura/escritura String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Devuelve o establece el estado del contenido de una presentación. Lectura/escritura String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Devuelve o establece el tipo de contenido de una presentación. Lectura/escritura String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Devuelve el número de propiedades personalizadas realmente contenidas en una colección. Solo lectura Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Devuelve la fecha en que se creó una presentación. Los valores están en UTC. Lectura/escritura DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Indica la agrupación de partes del documento y el número de partes en cada grupo. Solo lectura IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Especifica el número de diapositivas ocultas en un documento de presentación. Solo lectura Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Devuelve o establece la propiedad del documento HyperlinkBase. Lectura/escritura String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Especifica que uno o más hipervínculos en esta parte fueron actualizados exclusivamente en esta parte por un productor. El siguiente productor que abra este documento actualizará las relaciones de hipervínculos con los nuevos hipervínculos especificados en esta parte. Lectura/escritura Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Devuelve o establece la propiedad personalizada asociada a un nombre especificado. Lectura/escritura Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Devuelve o establece las palabras clave de una presentación. Lectura/escritura String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Devuelve la fecha en que una presentación se imprimió por última vez. Lectura/escritura DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Devuelve o establece el nombre de la última persona que modificó una presentación. Lectura/escritura String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Devuelve la fecha en que una presentación fue modificada por última vez. Los valores están en UTC. Solo lectura en caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). Puede modificarse a través de la instancia DocumentProperties devuelta por el método [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Consulte el ejemplo en el resumen del método [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Indica si los hipervínculos en un documento están actualizados. Establezca este elemento a **true** para indicar que los hipervínculos están actualizados. Establezca este elemento a **false** para indicar que los hipervínculos están desactualizados. Lectura/escritura Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Devuelve o establece la propiedad del gestor. Lectura/escritura String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Especifica el número total de clips de sonido o video presentes en el documento. Solo lectura Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Devuelve o establece el nombre de la aplicación. Lectura/escritura String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Especifica el número de diapositivas en una presentación que contienen notas. Solo lectura Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Especifica el número total de párrafos encontrados en un documento, si corresponde. Solo lectura Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Devuelve o establece el formato previsto de una presentación. Lectura/escritura String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Devuelve o establece el número de revisión de la presentación. Lectura/escritura Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Indica el modo de visualización de la miniatura del documento. Establezca este elemento a **true** para habilitar el escalado de la miniatura del documento a la pantalla. Establezca este elemento a **false** para habilitar el recorte de la miniatura del documento para mostrar solo las secciones que se ajustan a la pantalla. Lectura/escritura Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Determina si la presentación se comparte entre varias personas. Lectura/escritura Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Especifica el número total de diapositivas en un documento de presentación. Solo lectura Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Devuelve o establece el asunto de una presentación. Lectura/escritura String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Devuelve o establece el título de una presentación. Lectura/escritura String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Especifica el título de cada parte del documento. Estas partes no son partes del documento sino representaciones conceptuales de secciones del documento. Solo lectura string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Tiempo total de edición de una presentación. Lectura/escritura TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Especifica el número total de palabras contenidas en un documento. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Borra y establece valores predeterminados para todas las propiedades incorporadas. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Elimina todas las propiedades personalizadas. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Comprueba la presencia de una propiedad personalizada con un nombre especificado. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Devuelve el nombre de una propiedad personalizada en el índice especificado. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtiene un valor booleano con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtiene un valor DateTime con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtiene un valor double con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtiene un valor float con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtiene un valor entero con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtiene un valor string con nombre de las propiedades personalizadas. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Obtiene una matriz de etiquetas de sensibilidad de las propiedades personalizadas del documento (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Elimina una propiedad personalizada asociada a un nombre especificado. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Establece una propiedad personalizada booleana con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Establece una propiedad personalizada DateTime con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Establece una propiedad personalizada double con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Establece una propiedad personalizada float con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Establece una propiedad personalizada entera con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Establece una propiedad personalizada string con nombre. |

### Ver también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->