---  
title: InterruptionToken
second_title: Referencia de API de Aspose.Slides para .NET  
description: Esta clase representa el token a utilizar para señalar tareas de larga duración si se solicitó la interrupción.
type: docs  
weight: 7360  
url: /es/aspose.slides/interruptiontoken/
---  

## Clase InterruptionToken  

Esta clase representa el token a utilizar para señalar tareas de larga duración si se solicitó la interrupción.  

```csharp  
public class InterruptionToken : IInterruptionToken  
```  

## Propiedades  

| Nombre | Descripción |  
| --- | --- |  
| static [None](../../aspose.slides/interruptiontoken/none) { get; } | Representa un token de interrupción vacío. Las operaciones de larga duración nunca serán interrumpidas a través de [`Interrupt`](../interruptiontokensource/interrupt) cuando se utilice este token. |  
| [IsInterruptionRequested](../../aspose.slides/interruptiontoken/isinterruptionrequested) { get; } | Devuelve Boolean.true si se solicitó la interrupción. |  

## Métodos  

| Nombre | Descripción |  
| --- | --- |  
| [ThrowIfInterruptionRequested](../../aspose.slides/interruptiontoken/throwifinterruptionrequested)() | Lanza una OperationCanceledException si se solicitó la interrupción. |  

### Véase también  

* interface [IInterruptionToken](../iinterruptiontoken)  
* namespace [Aspose.Slides](../../aspose.slides)  
* assembly [Aspose.Slides](../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  