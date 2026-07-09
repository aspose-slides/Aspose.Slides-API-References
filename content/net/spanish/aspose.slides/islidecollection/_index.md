---
title: ISlideCollection
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa una colección de diapositivas.
type: docs
weight: 7050
url: /es/aspose.slides/islidecollection/
---
## ISlideCollection interfaz

Representa una colección de diapositivas.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`ISlide`](../islide). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Agrega una copia de una diapositiva especificada al final de la colección. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Agrega una copia de una diapositiva especificada al final de la colección. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Agrega una copia de una diapositiva especificada al final de la sección especificada. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Agrega una copia de una diapositiva origen especificada al final de la colección. Se seleccionará automáticamente la disposición apropiada del maestro especificado (la disposición apropiada es la que tiene el mismo Tipo o Nombre que la disposición de la diapositiva origen). Si no hay una disposición apropiada, entonces la disposición de la diapositiva origen será clonada (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Agrega una nueva diapositiva vacía al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Crea diapositivas a partir del documento PDF y las agrega al final de la colección considerando las opciones de importación PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Devuelve un índice de la diapositiva especificada en la colección. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Inserta una copia de una diapositiva especificada en la posición indicada de la colección. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición indicada de la colección. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserta una copia de una diapositiva origen especificada en la posición indicada de la colección. Se seleccionará automáticamente la disposición apropiada del maestro especificado (la disposición apropiada es la que tiene el mismo Tipo o Nombre que la disposición de la diapositiva origen). Si no hay una disposición apropiada, entonces la disposición de la diapositiva origen será clonada (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Inserta una copia de una diapositiva especificada en la posición indicada de la colección. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición indicada. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Elimina la primera aparición de un objeto específico de la colección. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Mueve la diapositiva de la colección a la posición especificada. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Mueve diapositivas de la colección a la posición especificada. Las diapositivas se colocarán a partir del índice en el orden en que aparecen en la lista. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Crea y devuelve una matriz con todas las diapositivas. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Crea y devuelve una matriz con todas las diapositivas del rango especificado. |

### Ver también

* interfaz [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfaz [ISlide](../islide)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->