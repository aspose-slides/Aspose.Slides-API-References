---
title: ColecciónDeDiapositivas
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una colección de diapositivas.
type: docs
weight: 9660
url: /es/aspose.slides/slidecollection/
---

## Clase ColecciónDeDiapositivas

Representa una colección de diapositivas.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Obtiene el número de elementos que realmente contiene la colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Agrega una copia de una diapositiva especificada al final de la colección. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Agrega una copia de una diapositiva especificada al final de la colección. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Agrega una copia de una diapositiva especificada al final de la sección especificada. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Agrega una copia de una diapositiva fuente especificada al final de la colección. Se seleccionará automáticamente un diseño apropiado del maestro especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el diseño de la diapositiva fuente). Si no hay un diseño apropiado, entonces se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es verdadero) o se lanzará PptxEditException (si allowCloneMissingLayout es falso). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Agrega una nueva diapositiva vacía al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección considerando las opciones de importación de pdf. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Copia todos los elementos de la colección al arreglo especificado. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Devuelve un índice de la diapositiva especificada en la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserta una copia de una diapositiva fuente especificada en la posición especificada de la colección. Se seleccionará automáticamente un diseño apropiado del maestro especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el diseño de la diapositiva fuente). Si no hay un diseño apropiado, entonces se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es verdadero) o se lanzará PptxEditException (si allowCloneMissingLayout es falso). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Elimina la primera ocurrencia de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Mueve la diapositiva de la colección a la posición especificada. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Mueve las diapositivas de la colección a la posición especificada. Las diapositivas se colocarán comenzando desde el índice en el orden en que aparecen en la lista. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Crea y devuelve un arreglo con todas las diapositivas en él. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Crea y devuelve un arreglo con todas las diapositivas del rango especificado en él. Un índice de la primera diapositiva a agregar. Un número de diapositivas a agregar. |

### Ver También

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [Presentation](../presentation)
* interfaz [ISlideCollection](../islidecollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->