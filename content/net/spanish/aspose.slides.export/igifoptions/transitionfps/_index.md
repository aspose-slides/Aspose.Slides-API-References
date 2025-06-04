---  
title: TransitionFps
second_title: Aspose.Sildes para referencia de API de .NET  
description: Obtiene o establece la FPS de transición frames/sec. El valor predeterminado es 25.
type: docs  
weight: 50  
url: /es/aspose.slides.export/igifoptions/transitionfps/
---  

## Propiedad IGifOptions.TransitionFps  

Obtiene o establece la FPS de transición [frames/sec]. El valor predeterminado es 25.  

```csharp  
public int TransitionFps { get; set; }  
```  

### Ejemplos  

```csharp  
[C#]  
using (Presentation pres = new Presentation("pres.pptx"))  
{  
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { TransitionFps = 60 });  
}  
```  

### Ver También  

* interfaz [IGifOptions](../../igifoptions)  
* espacio de nombres [Aspose.Slides.Export](../../igifoptions)  
* ensamblaje [Aspose.Slides](../../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  