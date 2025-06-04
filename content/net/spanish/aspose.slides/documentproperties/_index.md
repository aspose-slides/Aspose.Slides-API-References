---
title: DocumentProperties
second_title: Aspose.Slides para .NET API Reference
description: Representa las propiedades de una presentación.
type: docs
weight: 2700
url: /es/aspose.slides/documentproperties/
---

## DocumentProperties class

Representa las propiedades de una presentación.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocumentProperties](documentproperties)() | Inicializa una nueva instancia de la clase [`DocumentProperties`](../documentproperties). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Devuelve o establece la plantilla de una aplicación. Lectura/escritura String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Devuelve la versión de la aplicación. Solo lectura String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Devuelve o establece el autor de una presentación. Lectura/escritura String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Devuelve o establece la categoría de una presentación. Lectura/escritura String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Devuelve o establece los comentarios de una presentación. Lectura/escritura String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Devuelve o establece la propiedad de empresa. Lectura/escritura String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Devuelve o establece el estado del contenido de una presentación. Lectura/escritura String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Devuelve o establece el tipo de contenido de una presentación. Lectura/escritura String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Devuelve el número de propiedades personalizadas contenidas en una colección. Solo lectura Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Devuelve la fecha en que se creó una presentación. Los valores están en UTC. Lectura/escritura DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Indica el agrupamiento de partes del documento y el número de partes en cada grupo. Solo lectura IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Devuelve el número de diapositivas ocultas en un documento de presentación. Solo lectura Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Devuelve o establece la propiedad del documento HyperlinkBase. Lectura/escritura String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Especifica que uno o más hiperenlaces en esta parte se actualizaron exclusivamente en esta parte por un productor. El siguiente productor que abra este documento debe actualizar las relaciones de hiperenlace con los nuevos hiperenlaces especificados en esta parte. Lectura/escritura Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Devuelve o establece la propiedad personalizada asociada con un nombre especificado. Lectura/escritura Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Devuelve o establece las palabras clave de una presentación. Lectura/escritura String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Devuelve la fecha en que se imprimió la presentación por última vez. Lectura/escritura DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Devuelve o establece el nombre de la última persona que modificó una presentación. Lectura/escritura String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Devuelve la fecha en que se modificó por última vez una presentación. Los valores están en UTC. Solo lectura en caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). Se puede cambiar a través de la instancia de DocumentProperties devuelta por el método [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Consulte el ejemplo en el resumen del método [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Indica si los hiperenlaces en un documento están actualizados. Establezca este elemento en **true** para indicar que los hiperenlaces están actualizados. Establezca este elemento en **false** para indicar que los hiperenlaces están desactualizados. Lectura/escritura Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Devuelve o establece la propiedad de gerente. Lectura/escritura String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Devuelve el número total de clips de sonido o video que están presentes en el documento. Solo lectura Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Devuelve o establece el nombre de la aplicación. Lectura/escritura String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Devuelve el número de diapositivas en una presentación que contienen notas. Solo lectura Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Devuelve el número total de párrafos encontrados en un documento si corresponde. Solo lectura Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Devuelve o establece el formato previsto de una presentación. Lectura/escritura String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Devuelve o establece el número de revisión de la presentación. Lectura/escritura Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Indica el modo de visualización de la miniatura del documento. Establezca este elemento en **true** para habilitar el escalado de la miniatura del documento para la pantalla. Establezca este elemento en **false** para habilitar el recorte de la miniatura del documento para mostrar solo las secciones que se ajustan a la pantalla. Lectura/escritura Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Determina si la presentación está compartida entre varias personas. Lectura/escritura Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Devuelve el número total de diapositivas en un documento de presentación. Solo lectura Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Devuelve o establece el tema de una presentación. Lectura/escritura String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Devuelve o establece el título de una presentación. Lectura/escritura String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Especifica el título de cada parte del documento. Estas partes no son partes del documento, sino representaciones conceptuales de secciones del documento. Solo lectura string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Tiempo total de edición de una presentación. Lectura/escritura TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Devuelve el número total de palabras contenidas en un documento. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Limpia y establece valores predeterminados para todas las propiedades incorporadas. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Elimina todas las propiedades personalizadas. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Clona el objeto actual |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Clona el objeto actual |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Verifica la presencia de una propiedad personalizada con un nombre especificado. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Devuelve un nombre de propiedad personalizada en el índice especificado. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtiene un valor booleano nombrado de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtiene un valor DateTime nombrado de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtiene un valor double nombrado de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtiene un valor float nombrado de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtiene un valor entero nombrado de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtiene un valor cadena nombrado de las propiedades personalizadas. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Elimina una propiedad personalizada asociada con un nombre especificado. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Establece una propiedad personalizada booleana nombrada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Establece una propiedad personalizada DateTime nombrada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Establece una propiedad personalizada double nombrada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Establece una propiedad personalizada float nombrada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Establece una propiedad personalizada entera nombrada. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Establece una propiedad personalizada de cadena nombrada. |

### Ejemplos

El siguiente ejemplo muestra cómo acceder a las propiedades incorporadas de una presentación de PowerPoint.

```csharp
[C#]
// Instanciar la clase Presentation que representa la presentación
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Crear una referencia al objeto IDocumentProperties asociado con la presentación
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Mostrar las propiedades incorporadas
	Console.WriteLine("Categoría : " + documentProperties.Category);
	Console.WriteLine("Estado Actual : " + documentProperties.ContentStatus);
	Console.WriteLine("Fecha de Creación : " + documentProperties.CreatedTime);
	Console.WriteLine("Autor : " + documentProperties.Author);
	Console.WriteLine("Descripción : " + documentProperties.Comments);
}
```

El siguiente ejemplo muestra cómo modificar las propiedades incorporadas de una presentación de PowerPoint.

```csharp
[C#]
// Instanciar la clase Presentation que representa la presentación
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Crear una referencia al objeto IDocumentProperties asociado con la presentación
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Establecer las propiedades incorporadas
	documentProperties.Author = "Aspose.Slides para .NET";
	documentProperties.Title = "Modificando Propiedades de Presentación";
	documentProperties.Subject = "Tema de Aspose";
	// Guardar la presentación en un archivo
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IDocumentProperties](../idocumentproperties)
* interfaz [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->