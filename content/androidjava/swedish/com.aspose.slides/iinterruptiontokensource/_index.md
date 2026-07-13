---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the source of .
type: docs
url: /sv/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Representerar källan till [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getToken()](#getToken--) | Returnerar en ny token bunden till denna [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returnerar true om avbrott begärt, false annars. |
| [interrupt()](#interrupt--) | Initierar begäran om avbrott. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Returnerar en ny token bunden till denna [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Returnerar:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Returnerar true om avbrott begärt, false annars.

**Returnerar:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Initierar begäran om avbrott.