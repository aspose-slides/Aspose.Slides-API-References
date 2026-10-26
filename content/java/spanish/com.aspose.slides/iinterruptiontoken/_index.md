---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: Esta clase representa el token que se utiliza para señalar a tareas de larga duración si se ha solicitado la interrupción.
type: docs
url: /es/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Esta clase representa el token que se utiliza para señalar a tareas de larga duración si se ha solicitado la interrupción.
## Métodos

| Method | Descripción |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Devuelve true si se solicitó la interrupción. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lanza una excepción si se solicitó la interrupción. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Devuelve true si se solicitó la interrupción.

**Devuelve:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Lanza una excepción si se solicitó la interrupción.