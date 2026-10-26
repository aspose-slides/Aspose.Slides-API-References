---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: Esta clase representa el token que se utiliza para indicar a tareas de larga duración si se ha solicitado la interrupción.
type: docs
url: /es/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Esta clase representa el token que se utiliza para indicar a tareas de larga duración si se ha solicitado la interrupción.
## Métodos

| Método | Descripción |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Devuelve true si se ha solicitado la interrupción. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lanza una excepción si se ha solicitado la interrupción. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Devuelve true si se ha solicitado la interrupción.

**Devuelve:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Lanza una excepción si se ha solicitado la interrupción.