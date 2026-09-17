---
title: InterruptionToken class
second_title: Aspose.Slides para Python vía .NET Referencia de la API
description: 
type: docs
url: /es/aspose.slides/interruptiontoken/
---
## Clase InterruptionToken

Esta clase representa el token que se usa para señalizar a tareas de larga duración si se ha solicitado la interrupción.

El tipo InterruptionToken expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`none`](/slides/python-net/es/aspose.slides/interruptiontoken/none/) | Representa un token de interrupción vacío.<br/>            Las operaciones de larga duración nunca serán interrumpidas a través de [`InterruptionTokenSource.interrupt`](/slides/python-net/es/aspose.slides/interruptiontokensource/interrupt)<br/>            al usar este token. |
| [`is_interruption_requested`](/slides/python-net/es/aspose.slides/interruptiontoken/is_interruption_requested/) | Devuelve **bool**.true si se solicitó la interrupción. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/es/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Lanza una OperationCanceledException si se solicitó la interrupción. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)