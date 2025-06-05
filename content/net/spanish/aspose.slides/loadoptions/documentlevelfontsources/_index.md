---  
title: DocumentLevelFontSources
second_title: Aspose.Slides para .NET Referencia de API  
description: Especifica fuentes para fuentes externas que se utilizarán en la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones
type: docs  
weight: 80  
url: /es/aspose.slides/loadoptions/documentlevelfontsources/
---  

## LoadOptions.DocumentLevelFontSources property  

Especifica fuentes para fuentes externas que se utilizarán en la presentación. Estas fuentes están disponibles para la presentación durante toda su vida útil y no se comparten con otras presentaciones  

```csharp  
public IFontSources DocumentLevelFontSources { get; set; }  
```  

### Ejemplos  

El siguiente ejemplo muestra cómo especificar fuentes personalizadas utilizadas con la Presentación de PowerPoint.  

```csharp  
[C#]  
byte[] memoryFont1 = File.ReadAllBytes("customfonts\\CustomFont1.ttf");  
byte[] memoryFont2 = File.ReadAllBytes("customfonts\\CustomFont2.ttf");  
LoadOptions loadOptions = new LoadOptions();  
loadOptions.DocumentLevelFontSources.FontFolders = new string[] { "assets\\fonts", "global\\fonts" };  
loadOptions.DocumentLevelFontSources.MemoryFonts = new byte[][] { memoryFont1, memoryFont2 };  
using (IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions))  
{  
    //trabajar con la presentación  
    //CustomFont1, CustomFont2, así como fuentes de las carpetas assets\fonts y global\fonts y sus subcarpetas están disponibles para la presentación  
}  
```  

### Ver También  

* interface [IFontSources](../../ifontsources)  
* class [LoadOptions](../../loadoptions)  
* namespace [Aspose.Slides](../../loadoptions)  
* assembly [Aspose.Slides](../../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  