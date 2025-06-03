---  
title: IFontsManager
second_title: Referencia de API de Aspose.Slides para .NET  
description: Administra fuentes a través de la presentación.
type: docs  
weight: 5730  
url: /es/aspose.slides/ifontsmanager/
---  

## Interfaz IFontsManager  

Administra fuentes a través de la presentación.  

```csharp  
public interface IFontsManager  
```  

## Propiedades  

| Nombre | Descripción |  
| --- | --- |  
| [FontFallBackRulesCollection](../../aspose.slides/ifontsmanager/fontfallbackrulescollection) { get; set; } | Representa la colección de reglas FontFallBack de un usuario para gestionar colecciones de fuentes para sustituciones adecuadas mediante la funcionalidad de retroceso. Lectura/escritura [`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |  
| [FontSubstRuleList](../../aspose.slides/ifontsmanager/fontsubstrulelist) { get; set; } | Sustituciones de fuentes a utilizar al renderizar. Lectura/escritura [`IFontSubstRuleCollection`](../ifontsubstrulecollection). |  

## Métodos  

| Nombre | Descripción |  
| --- | --- |  
| [AddEmbeddedFont](../../aspose.slides/ifontsmanager/addembeddedfont#addembeddedfont_1)(byte[], EmbedFontCharacters) | Agrega la fuente incrustada. Ten en cuenta que al agregar cualquier fuente, la mayoría de las fuentes están protegidas por derechos de autor. Primero localiza la licencia de una fuente de antemano y verifica que se pueden transferir libremente a otra máquina. Se puede lanzar una ArgumentException si los datos de la fuente son null o si esta fuente ya está incrustada. |  
| [AddEmbeddedFont](../../aspose.slides/ifontsmanager/addembeddedfont#addembeddedfont)(IFontData, EmbedFontCharacters) | Agrega la fuente incrustada. Ten en cuenta que al copiar cualquier fuente, la mayoría de las fuentes están protegidas por derechos de autor. Primero localiza la licencia de una fuente de antemano y verifica que se pueden transferir libremente a otra máquina. Se puede lanzar una ArgumentException si los datos de la fuente son null o si esta fuente ya está incrustada. |  
| [GetEmbeddedFonts](../../aspose.slides/ifontsmanager/getembeddedfonts)() | Devuelve las fuentes incrustadas en la presentación. |  
| [GetFontBytes](../../aspose.slides/ifontsmanager/getfontbytes)(IFontData, FontStyle) | Recupera el arreglo de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente específicos. |  
| [GetFontEmbeddingLevel](../../aspose.slides/ifontsmanager/getfontembeddinglevel)(byte[], string) | Determina el nivel de incrustación de una fuente a partir del arreglo de bytes dado y el nombre de la fuente. |  
| [GetFonts](../../aspose.slides/ifontsmanager/getfonts)() | Devuelve las fuentes utilizadas en la presentación. |  
| [GetSubstitutions](../../aspose.slides/ifontsmanager/getsubstitutions)() | Obtiene la información sobre las fuentes que serán reemplazadas en la renderización de la presentación. |  
| [RemoveEmbeddedFont](../../aspose.slides/ifontsmanager/removeembeddedfont)(IFontData) | Elimina la fuente incrustada. |  
| [ReplaceFont](../../aspose.slides/ifontsmanager/replacefont#replacefont_1)(IFontSubstRule) | Reemplaza la fuente en la presentación utilizando la información proporcionada en [`IFontSubstRule`](../ifontsubstrule). |  
| [ReplaceFont](../../aspose.slides/ifontsmanager/replacefont#replacefont_2)(IFontSubstRuleCollection) | Reemplaza la fuente en la presentación utilizando la información proporcionada en la colección de [`IFontSubstRule`](../ifontsubstrule). |  
| [ReplaceFont](../../aspose.slides/ifontsmanager/replacefont#replacefont)(IFontData, IFontData) | Reemplaza la fuente en la presentación. |  

### Vea También  

* espacio de nombres [Aspose.Slides](../../aspose.slides)  
* ensamblaje [Aspose.Slides](../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  