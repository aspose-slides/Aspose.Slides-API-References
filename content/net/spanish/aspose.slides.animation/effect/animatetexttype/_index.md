---  
title: AnimateTextType
second_title: Referencia de API de Aspose.Slides para .NET  
description: Define un tipo de texto animado para el efecto. El texto de la forma se puede animar por letra, por palabra o todo a la vez. Leer/escribir AnimateTextTypeaspose.slides.animation/effect/animatetexttype.
type: docs
weight: 30  
url: /es/aspose.slides.animation/effect/animatetexttype/
---  

## Propiedad Effect.AnimateTextType  

Define un tipo de texto animado para el efecto. El texto de la forma se puede animar por letra, por palabra o todo a la vez. Leer/escribir `AnimateTextType`.  

```csharp  
public AnimateTextType AnimateTextType { get; set; }  
```  

### Ejemplos  

```csharp  
[C#]  
using (Presentation presentation = new Presentation("demo.pptx"))  
{  
    // Obtener el primer efecto de la primera diapositiva.  
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];  
    
    // Cambiar el tipo de texto animado a "Por letra"  
    firstSlideEffect.AnimateTextType = AnimateTextType.ByLetter;  
}  
```  

### Véase También  

* enum [AnimateTextType](../../animatetexttype)  
* class [Effect](../../effect)  
* namespace [Aspose.Slides.Animation](../../effect)  
* assembly [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  