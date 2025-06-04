---  
title: FontsManager
second_title: Aspose.Sildes para .NET Referencia de API  
description: Devuelve el administrador de fuentes. Solo lectura IFontsManageraspose.slides/ifontsmanager.
type: docs  
weight: 110  
url: /es/aspose.slides/presentation/fontsmanager/
---  

## Propiedad Presentation.FontsManager  

Devuelve el administrador de fuentes. Solo lectura [`IFontsManager`](../../ifontsmanager).  

```csharp  
public IFontsManager FontsManager { get; }  
```  

### Ejemplos  

El siguiente ejemplo muestra cómo agregar fuentes incrustadas a una presentación de PowerPoint.  

```csharp  
[C#]  
// Cargar presentación  
using (Presentation presentation = new Presentation("Fonts.pptx"))  
{  
	// Cargar fuente fuente de origen que se va a reemplazar  
	IFontData sourceFont = new FontData("Arial");  
	IFontData[] allFonts = presentation.FontsManager.GetFonts();  
	IFontData[] embeddedFonts = presentation.FontsManager.GetEmbeddedFonts();  
	foreach (IFontData font in allFonts)  
	{  
		if (!embeddedFonts.Contains(font))  
		{  
			presentation.FontsManager.AddEmbeddedFont(font, EmbedFontCharacters.All);  
		}  
	}  
	// Guardar la presentación  
	presentation.Save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);  
}  
```  

### Ver también  

* interfaz [IFontsManager](../../ifontsmanager)  
* clase [Presentation](../../presentation)  
* espacio de nombres [Aspose.Slides](../../presentation)  
* ensamblado [Aspose.Slides](../../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  