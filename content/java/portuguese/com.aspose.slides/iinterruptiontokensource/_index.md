---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Represents the source of .
type: docs
url: /pt/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Representa a origem de [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Métodos

| Método | Descrição |
| --- | --- |
| [getToken()](#getToken--) | Retorna um novo token vinculado a este [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retorna true se a interrupção foi solicitada, false caso contrário. |
| [interrupt()](#interrupt--) | Inicializa solicitação de interrupção. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Retorna um novo token vinculado a este [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Retorna:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Retorna true se a interrupção foi solicitada, false caso contrário.

**Retorna:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Inicializa solicitação de interrupção.