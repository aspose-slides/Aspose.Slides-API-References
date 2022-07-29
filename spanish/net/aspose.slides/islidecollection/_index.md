---
title: ISlideCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una colección de diapositivas.
type: docs
weight: 6470
url: /es/net/aspose.slides/islidecollection/
---
## ISlideCollection interface

Representa una colección de diapositivas.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura[`ISlide`](../islide) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Agrega una copia de una diapositiva específica al final de la colección. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Agrega una copia de una diapositiva específica al final de la colección. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Agrega una copia de una diapositiva especificada al final de la sección especificada. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Agrega una copia de una diapositiva de origen especificada al final de la colección. El diseño adecuado se seleccionará automáticamente del patrón especificado (el diseño apropiado es el diseño con el mismo tipo o nombre que del diseño de la diapositiva de origen). Si no hay un diseño adecuado, se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se generará una excepción PptxEditException (si allowCloneMissingLayout es falso). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Agrega una nueva diapositiva vacía al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(string) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Devuelve un índice de la diapositiva especificada en la colección. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserta una copia de una diapositiva de origen especificada en la posición especificada de la colección. El diseño apropiado se seleccionará automáticamente del patrón especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que del diseño de la diapositiva de origen). Si no hay un diseño adecuado, se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se generará una excepción PptxEditException (si allowCloneMissingLayout es falso). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Elimina la primera aparición de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Mueve la diapositiva de la colección a la posición especificada. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Mueve las diapositivas de la colección a la posición especificada. Las diapositivas se colocarán comenzando desde el índice en el orden en que aparecen en la lista. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Crea y devuelve una matriz con todas las diapositivas. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Crea y devuelve una matriz con todas las diapositivas del rango especificado. |

### Ver también

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
