---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Stellt die Quelle von .
type: docs
url: /de/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Stellt die Quelle von [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) dar.
## Methods

| Methode | Beschreibung |
| --- | --- |
| [getToken()](#getToken--) | Gibt ein neues Token zurück, das an dieses [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) gebunden ist. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Gibt true zurück, wenn eine Unterbrechung angefordert wurde, andernfalls false. |
| [interrupt()](#interrupt--) | Initialisiert die Anforderung für eine Unterbrechung. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Gibt ein neues Token zurück, das an dieses [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) gebunden ist.

**Rückgabe:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Gibt true zurück, wenn eine Unterbrechung angefordert wurde, andernfalls false.

**Rückgabe:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Initialisiert die Anforderung für eine Unterbrechung.