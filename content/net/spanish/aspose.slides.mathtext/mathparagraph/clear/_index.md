---  
title: Clear
second_title: Referencia de API de Aspose.Slides para .NET  
description: Elimina todos los elementos de la colección.
type: docs  
weight: 60  
url: /es/aspose.slides.mathtext/mathparagraph/clear/
---  

## Método MathParagraph.Clear  

Elimina todos los elementos de la colección.  

```csharp  
public void Clear()  
```  

### Ejemplos  

Ejemplo:  

```csharp  
[C#]  
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);  
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;  
mathParagraph.Add(new MathBlock(new MathematicalText("block1")));  
mathParagraph.Add(new MathBlock(new MathematicalText("block2")));  
mathParagraph.Clear();  
```  

### Ver también  

* clase [MathParagraph](../../mathparagraph)  
* espacio de nombres [Aspose.Slides.MathText](../../mathparagraph)  
* ensamblado [Aspose.Slides](../../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  