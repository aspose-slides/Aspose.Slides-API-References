---
title: IInterruptionToken
second_title: Aspose.Slides para Android via Referência de API Java
description: Esta classe representa o token a ser usado para sinalizar tarefas de longa duração se a interrupção foi solicitada.
type: docs
url: /pt/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Esta classe representa o token a ser usado para sinalizar tarefas de longa duração se a interrupção foi solicitada.
## Métodos

| Método | Descrição |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retorna verdadeiro se a interrupção foi solicitada. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lança uma exceção se a interrupção foi solicitada. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Retorna verdadeiro se a interrupção foi solicitada.

**Retorna:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Lança uma exceção se a interrupção foi solicitada.