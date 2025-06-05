---  
title: IParagraphCollection
second_title: Referencia de API de Aspose.Slides para .NET  
description: Representa una colección de párrafos.
type: docs  
weight: 6370  
url: /es/aspose.slides/iparagraphcollection/
---  

## Interfaz IParagraphCollection  

Representa una colección de párrafos.  

```csharp  
public interface IParagraphCollection : IEnumerable<IParagraph>, ISlideComponent  
```  

## Propiedades  

| Nombre | Descripción |  
| --- | --- |  
| [AsIEnumerable](../../aspose.slides/iparagraphcollection/asienumerable) { get; } | Devuelve la interfaz IEnumerable. Solo lectura IEnumerable. |  
| [AsISlideComponent](../../aspose.slides/iparagraphcollection/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura [`ISlideComponent`](../islidecomponent). |  
| [Count](../../aspose.slides/iparagraphcollection/count) { get; } | Obtiene la cantidad de elementos que realmente contiene la colección. Solo lectura Int32. |  
| [Item](../../aspose.slides/iparagraphcollection/item) { get; } | Obtiene el elemento en el índice especificado. |  

## Métodos  

| Nombre | Descripción |  
| --- | --- |  
| [Add](../../aspose.slides/iparagraphcollection/add#add_1)(IParagraph) | Añade un párrafo al final de la colección. |  
| [Add](../../aspose.slides/iparagraphcollection/add#add)(IParagraphCollection) | Añade el contenido de ParagraphCollection al final de la colección. |  
| [AddFromHtml](../../aspose.slides/iparagraphcollection/addfromhtml#addfromhtml)(string) | Añade texto de la cadena html especificada a la colección. |  
| [AddFromHtml](../../aspose.slides/iparagraphcollection/addfromhtml#addfromhtml_1)(string, IExternalResourceResolver, string) | Añade texto de la cadena html especificada a la colección. |  
| [Clear](../../aspose.slides/iparagraphcollection/clear)() | Elimina todos los elementos de la colección. |  
| [ExportToHtml](../../aspose.slides/iparagraphcollection/exporttohtml)(int, int, ITextToHtmlConversionOptions) | Convierte los párrafos especificados a HTML y lo devuelve como objeto String. |  
| [Insert](../../aspose.slides/iparagraphcollection/insert#insert)(int, IParagraph) | Inserta un párrafo en la colección en el índice especificado. |  
| [Insert](../../aspose.slides/iparagraphcollection/insert#insert_1)(int, IParagraphCollection) | Inserta el contenido de ParagraphCollection en la colección en el índice especificado. |  
| [Remove](../../aspose.slides/iparagraphcollection/remove)(IParagraph) | Elimina la primera ocurrencia de un párrafo específico. |  
| [RemoveAt](../../aspose.slides/iparagraphcollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |  

### Véase También  

* interfaz [IParagraph](../iparagraph)  
* interfaz [ISlideComponent](../islidecomponent)  
* espacio de nombres [Aspose.Slides](../../aspose.slides)  
* ensamblado [Aspose.Slides](../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  