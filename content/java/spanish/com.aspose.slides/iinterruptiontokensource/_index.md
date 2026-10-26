---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Representa la fuente de .
type: docs
url: /es/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Representa la fuente de [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).

## Métodos

| Método | Descripción |
| --- | --- |
| [getToken()](#getToken--) | Devuelve un nuevo token vinculado a este [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Devuelve true si se solicitó una interrupción, false en caso contrario. |
| [interrupt()](#interrupt--) | Inicializa la solicitud de interrupción. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Devuelve un nuevo token vinculado a este [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Devuelve:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Devuelve true si se solicitó una interrupción, false en caso contrario.

**Devuelve:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Inicializa la solicitud de interrupción.