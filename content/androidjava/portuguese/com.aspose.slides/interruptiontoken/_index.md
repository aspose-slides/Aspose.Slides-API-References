---
title: InterruptionToken
second_title: Referência da API Java do Aspose.Slides para Android
description: Esta classe representa o token a ser usado para sinalizar tarefas de longa execução se a interrupção foi solicitada.
type: docs
url: /pt/com.aspose.slides/interruptiontoken/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Esta classe representa o token a ser usado para sinalizar tarefas de longa execução se a interrupção foi solicitada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getNone()](#getNone--) | Representa um token de interrupção vazio. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retorna verdadeiro se a interrupção foi solicitada. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Lança uma exceção se a interrupção foi solicitada. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Representa um token de interrupção vazio.

--------------------

Operações de longa duração nunca serão interrompidas via [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) ao usar este token.

**Retorna:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Retorna verdadeiro se a interrupção foi solicitada.

**Retorna:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Lança uma exceção se a interrupção foi solicitada.