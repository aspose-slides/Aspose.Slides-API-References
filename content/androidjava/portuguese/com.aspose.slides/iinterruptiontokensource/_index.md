---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Representa a fonte de .
type: docs
url: /pt/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Representa a fonte de [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Métodos

| Método | Descrição |
| --- | --- |
| [getToken()](#getToken--) | Retorna novo token vinculado a este [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retorna verdadeiro se a interrupção foi solicitada, falso caso contrário. |
| [interrupt()](#interrupt--) | Inicializa solicitação de interrupção. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Retorna novo token vinculado a este [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Retorna:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Retorna verdadeiro se a interrupção foi solicitada, falso caso contrário.

**Retorna:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Inicializa solicitação de interrupção.