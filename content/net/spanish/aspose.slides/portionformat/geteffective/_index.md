---  
title: GetEffective
second_title: Referencia de API de Aspose.Slides para .NET  
description: Obtiene datos de formato de porción efectiva con la herencia aplicada.
type: docs
weight: 70  
url: /es/aspose.slides/portionformat/geteffective/
---  
  
## Método PortionFormat.GetEffective  
  
Obtiene datos de formato de porción efectiva con la herencia aplicada.  
  
```csharp  
public IPortionFormatEffectiveData GetEffective()  
```  
  
### Valor de retorno  
  
Un [`IPortionFormatEffectiveData`](../../iportionformateffectivedata).  
  
### Ejemplos  
  
Este ejemplo demuestra cómo obtener algunas propiedades de formato de porción efectiva.  
  
```csharp  
[C#]  
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))  
{  
	IAutoShape shape = pres.Slides[0].Shapes[0] as IAutoShape;  
	IPortionFormatEffectiveData effectivePortionFormat = shape.TextFrame.Paragraphs[0].Portions[0].PortionFormat.GetEffective();  
  
	Console.WriteLine("Fuente latina: " + effectivePortionFormat.LatinFont.FontName);  
	Console.WriteLine("Altura de fuente: " + effectivePortionFormat.FontHeight);  
	Console.WriteLine("Tipo de relleno: " + effectivePortionFormat.FillFormat.FillType);  
}  
```  
  
### Véase también  
  
* interfaz [IPortionFormatEffectiveData](../../iportionformateffectivedata)  
* clase [PortionFormat](../../portionformat)  
* espacio de nombres [Aspose.Slides](../../portionformat)  
* ensamblado [Aspose.Slides](../../../)  
  
<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  