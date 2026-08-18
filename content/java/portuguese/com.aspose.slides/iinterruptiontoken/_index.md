---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /pt/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Esta classe representa o token a ser usado para sinalizar tarefas de longa duração se a interrupção foi solicitada.
## Métodos

| Método | Descrição |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retorna true se a interrupção foi solicitada. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lança um se a interrupção foi solicitada. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Retorna true se a interrupção foi solicitada.

**Retorna:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

Lança um se a interrupção foi solicitada.