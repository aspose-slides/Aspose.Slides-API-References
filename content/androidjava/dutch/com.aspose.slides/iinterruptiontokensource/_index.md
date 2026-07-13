---
title: IInterruptionTokenSource
second_title: Aspose.Slides voor Android via Java API-referentie
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
| [getToken()](#getToken--) | Retourneert een nieuw token dat aan deze [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) is gekoppeld. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retourneert true als onderbreking is aangevraagd, anders false. |
| [interrupt()](#interrupt--) | Initialiseer aanvraag voor onderbreking. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Retourneert een nieuw token dat aan deze [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) is gekoppeld.

**Retour:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Retourneert true als onderbreking is aangevraagd, anders false.

**Retour:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Initialiseer aanvraag voor onderbreking.