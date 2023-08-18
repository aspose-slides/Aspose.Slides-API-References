---
title: SlideCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una colección de diapositivas.
type: docs
weight: 9190
url: /es/aspose.slides/slidecollection/
---
## SlideCollection class

Representa una colección de diapositivas.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Obtiene el número de elementos realmente contenidos en la colección. Solo lecturaInt32 . |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lecturaBoolean . |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura[`Slide`](../slide) . |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lecturaObject . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Agrega una copia de una diapositiva específica al final de la colección. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Agrega una copia de una diapositiva específica al final de la colección. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Agrega una copia de una diapositiva especificada al final de la sección especificada. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Agrega una copia de una diapositiva de origen especificada al final de la colección. El diseño adecuado se seleccionará automáticamente del patrón especificado (el diseño apropiado es el diseño con el mismo tipo o nombre que del diseño de la diapositiva de origen). Si no hay un diseño adecuado, se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se generará una excepción PptxEditException (si allowCloneMissingLayout es falso). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Agrega una nueva diapositiva vacía al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(string) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Copia todos los elementos de la colección a la matriz especificada. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Devuelve un índice de la diapositiva especificada en la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserta una copia de una diapositiva de origen especificada en la posición especificada de la colección. El diseño apropiado se seleccionará automáticamente del patrón especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que del diseño de la diapositiva de origen). Si no hay un diseño adecuado, se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se generará una excepción PptxEditException (si allowCloneMissingLayout es falso). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Elimina la primera aparición de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Mueve la diapositiva de la colección a la posición especificada. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Mueve las diapositivas de la colección a la posición especificada. Las diapositivas se colocarán comenzando desde el índice en el orden en que aparecen en la lista. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Crea y devuelve una matriz con todas las diapositivas. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Crea y devuelve una matriz con todas las diapositivas del rango especificado. Un índice de una primera diapositiva para agregar.Una serie de diapositivas para agregar. |

### Ver también

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
