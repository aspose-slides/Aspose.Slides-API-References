---
title: IInterruptionTokenSource
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de bron van .
type: docs
url: /nl/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Stelt de bron van [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getToken()](#getToken--) | Retourneert een nieuw token gebonden aan dit [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retourneert true als onderbreking aangevraagd is, anders false. |
| [interrupt()](#interrupt--) | Initialiseer aanvraag voor onderbreking. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Retourneert een nieuw token gebonden aan dit [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Retourneert:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Retourneert true als onderbreking aangevraagd is, anders false.

**Retourneert:**  
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Initialiseer aanvraag voor onderbreking.