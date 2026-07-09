---
title: SlideCollection
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa una colección de diapositivas.
type: docs
weight: 9970
url: /es/aspose.slides/slidecollection/
---
## SlideCollection clase

Representa una colección de diapositivas.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Obtiene el número de elementos realmente contenidos en la colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Añade una copia de una diapositiva especificada al final de la colección. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Añade una copia de una diapositiva especificada al final de la colección. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Añade una copia de una diapositiva especificada al final de la sección especificada. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Añade una copia de una diapositiva origen especificada al final de la colección. El diseño apropiado se seleccionará automáticamente del maestro especificado (el diseño apropiado es el diseño con el mismo Type o Name que el diseño de la diapositiva origen). Si no existe un diseño apropiado, entonces el diseño de la diapositiva origen se clonará (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Añade una nueva diapositiva vacía al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Crea diapositivas a partir del documento PDF y las añade al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Crea diapositivas a partir del documento PDF y las añade al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Crea diapositivas a partir del documento PDF y las añade al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Crea diapositivas a partir del documento PDF y las añade al final de la colección teniendo en cuenta las opciones de importación PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Copia todos los elementos de la colección al arreglo especificado. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Devuelve un enumerador que recorre la colección. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Devuelve el índice de la diapositiva especificada en la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserta una copia de una diapositiva origen especificada en la posición especificada de la colección. El diseño apropiado se seleccionará automáticamente del maestro especificado (el diseño apropiado es el diseño con el mismo Type o Name que el diseño de la diapositiva origen). Si no existe un diseño apropiado, entonces el diseño de la diapositiva origen se clonará (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Elimina la primera aparición de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Mueve la diapositiva dentro de la colección a la posición especificada. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Mueve diapositivas de la colección a la posición especificada. Las diapositivas se colocarán a partir del índice en el orden en que aparecen en la lista. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Crea y devuelve un arreglo con todas las diapositivas. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Crea y devuelve un arreglo con todas las diapositivas del rango especificado. Un índice de la primera diapositiva a agregar. Un número de diapositivas a agregar. |

### Ver también

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [Presentation](../presentation)
* interfaz [ISlideCollection](../islidecollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->