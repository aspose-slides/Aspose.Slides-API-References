---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Représente la source de .
type: docs
url: /fr/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Représente la source de [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getToken()](#getToken--) | Renvoie un nouveau token lié à ce [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Renvoie true si interruption demandée, false sinon. |
| [interrupt()](#interrupt--) | Initialiser la demande d’interruption. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Renvoie un nouveau token lié à ce [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Renvoie:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Renvoie true si interruption demandée, false sinon.

**Renvoie:**  
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Initialiser la demande d’interruption.