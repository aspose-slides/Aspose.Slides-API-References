---
title: InterruptionToken
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Esta clase representa el token que se usa para señalar tareas de larga duración si se solicitó la interrupción.
type: docs
url: /es/com.aspose.slides/interruptiontoken/
---
**Herencia:**  
java.lang.Object

**Todas las interfaces implementadas:**  
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)  
```
public class InterruptionToken implements IInterruptionToken
```

Esta clase representa el token que se usa para señalar tareas de larga duración si se solicitó la interrupción.

## Métodos

| Método | Descripción |
| --- | --- |
| [getNone()](#getNone--) | Representa un token de interrupción vacío. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Devuelve true si se solicitó la interrupción. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lanza una excepción si se solicitó la interrupción. |

### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Representa un token de interrupción vacío.

--------------------

Las operaciones de larga duración nunca se interrumpirán mediante [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) al usar este token.

**Devuelve:**  
[InterruptionToken](../../com.aspose.slides/interruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Devuelve true si se solicitó la interrupción.

**Devuelve:**  
boolean

### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Lanza una excepción si se solicitó la interrupción.