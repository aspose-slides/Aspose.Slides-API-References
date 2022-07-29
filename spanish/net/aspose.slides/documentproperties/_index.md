---
title: DocumentProperties
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa las propiedades de una presentación.
type: docs
weight: 2640
url: /es/net/aspose.slides/documentproperties/
---
## DocumentProperties class

Representa las propiedades de una presentación.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocumentProperties](documentproperties)() | Inicializa nueva instancia de clase[`DocumentProperties`](../documentproperties) . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Devuelve o establece la plantilla de una aplicación. Lectura/escrituraString . |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Devuelve la versión de la aplicación. Solo lecturaString . |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Devuelve o establece el autor de una presentación. Lectura/escrituraString . |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Devuelve o establece la categoría de una presentación. Lectura/escrituraString . |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Devuelve o establece los comentarios de una presentación. Lectura/escrituraString . |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Devuelve o establece la propiedad de la empresa. Lectura/escrituraString . |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Devuelve o establece el estado del contenido de una presentación. Lectura/escrituraString . |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Devuelve o establece el tipo de contenido de una presentación. Lectura/escrituraString . |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Devuelve el número de propiedades personalizadas realmente contenidas en una colección. Solo lecturaInt32 . |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Devuelve la fecha en que se creó una presentación. Lectura/escrituraDateTime . |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Devuelve o establece la propiedad del documento HyperlinkBase. Lectura/escrituraString . |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Devuelve o establece la propiedad personalizada asociada con un nombre especificado. Lectura/escrituraObject . |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Devuelve o establece las palabras clave de una presentación. Lectura/escrituraString . |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Devuelve la fecha en que se imprimió una presentación por última vez. Lectura/escrituraDateTime . |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Devuelve o establece el nombre de la última persona que modificó una presentación. Lectura/escrituraString . |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Devuelve la fecha en que se modificó una presentación por última vez. Solo lectura en el caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). Se puede cambiar a través de la instancia de DocumentProperties que regresa por método[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Consulte el ejemplo en[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties)resumen del método. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Devuelve o establece la propiedad del administrador. Lectura/escrituraString . |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Devuelve o establece el nombre de la aplicación. Lectura/escrituraString . |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Devuelve o establece el formato deseado de una presentación. Lectura/escrituraString . |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Devuelve o establece el número de revisión de la presentación. Lectura/escrituraInt32 . |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Determina si la presentación se comparte entre varias personas. Lectura/escrituraBoolean . |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Devuelve o establece el asunto de una presentación. Lectura/escrituraString . |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Devuelve o establece el título de una presentación. Lectura/escrituraString . |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Tiempo total de edición de una presentación. Lectura/escrituraTimeSpan . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Borra y establece los valores predeterminados para todas las propiedades integradas. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Elimina todas las propiedades personalizadas. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Clona el objeto actual |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Clona el objeto actual |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Comprobar los regalos de una propiedad personalizada con un nombre especificado. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Devuelve un nombre de propiedad personalizado en el índice especificado. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtiene un valor booleano con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtiene un valor DateTime con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtiene un valor doble con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtiene un valor flotante con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtiene un valor entero con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtiene un valor de cadena con nombre de las propiedades personalizadas. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Eliminar una propiedad personalizada asociada con un nombre especificado. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Establece una propiedad personalizada booleana con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Establece una propiedad personalizada DateTime con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Establece una propiedad personalizada doble con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Establece una propiedad personalizada flotante con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Establece una propiedad personalizada de entero con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Establece una propiedad personalizada de cadena con nombre. |

### Ver también

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
