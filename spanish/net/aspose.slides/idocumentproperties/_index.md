---
title: IDocumentProperties
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa las propiedades de una presentación.
type: docs
weight: 5210
url: /es/net/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Representa las propiedades de una presentación.

```csharp
public interface IDocumentProperties
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Devuelve o establece la plantilla de una aplicación. Lectura/escrituraString . |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Devuelve la versión de la aplicación. Solo lecturaString . |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Devuelve o establece el autor de una presentación. Lectura/escrituraString . |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Devuelve o establece la categoría de una presentación. Lectura/escrituraString . |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Devuelve o establece los comentarios de una presentación. Lectura/escrituraString . |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Devuelve o establece la propiedad de la empresa. Lectura/escrituraString . |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Devuelve o establece el estado del contenido de una presentación. Lectura/escrituraString . |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Devuelve o establece el tipo de contenido de una presentación. Lectura/escrituraString . |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Devuelve el número de propiedades personalizadas realmente contenidas en una colección. Solo lecturaInt32 . |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Devuelve la fecha en que se creó una presentación. Lectura/escrituraDateTime . |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Devuelve o establece la propiedad del documento HyperlinkBase. Lectura/escrituraString . |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Devuelve o establece la propiedad personalizada asociada con un nombre especificado. Lectura/escrituraObject . |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Devuelve o establece las palabras clave de una presentación. Lectura/escrituraString . |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Devuelve la fecha en que se imprimió una presentación por última vez. Lectura/escrituraDateTime . |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Devuelve o establece el nombre de la última persona que modificó una presentación. Lectura/escrituraString . |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Devuelve la fecha en que se modificó una presentación por última vez. Solo lectura en el caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). Se puede cambiar a través de la instancia de DocumentProperties que regresa por método[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Consulte el ejemplo en[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties)resumen del método. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Devuelve o establece la propiedad del administrador. Lectura/escrituraString . |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Devuelve o establece el nombre de la aplicación. Lectura/escrituraString . |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Devuelve o establece el formato deseado de una presentación. Lectura/escrituraString . |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Devuelve o establece el número de revisión de la presentación. Lectura/escrituraInt32 . |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Determina si la presentación se comparte entre varias personas. Lectura/escrituraBoolean . |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Devuelve o establece el asunto de una presentación. Lectura/escrituraString . |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Devuelve o establece el título de una presentación. Lectura/escrituraString . |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Tiempo total de edición de una presentación. Lectura/escrituraTimeSpan . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Borra y establece los valores predeterminados para todas las propiedades integradas. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Elimina todas las propiedades personalizadas. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Comprobar los regalos de una propiedad personalizada con un nombre especificado. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Devuelve un nombre de propiedad personalizado en el índice especificado. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtiene un valor booleano con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtiene un valor DateTime con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtiene un valor doble con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtiene un valor flotante con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtiene un valor entero con nombre de las propiedades personalizadas. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtiene un valor de cadena con nombre de las propiedades personalizadas. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Eliminar una propiedad personalizada asociada con un nombre especificado. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Establece una propiedad personalizada booleana con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Establece una propiedad personalizada DateTime con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Establece una propiedad personalizada doble con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Establece una propiedad personalizada flotante con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Establece una propiedad personalizada de entero con nombre. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Establece una propiedad personalizada de cadena con nombre. |

### Ver también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
