---
title: InterruptionTokenSource
second_title: Aspose.Slides för Java API-referens
description: Representerar källan till .
type: docs
url: /sv/com.aspose.slides/interruptiontokensource/
---
**Arv:**
java.lang.Object
```
public class InterruptionTokenSource
```

Representerar källan till [InterruptionToken](../../com.aspose.slides/interruptiontoken).
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | Skapar en ny [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getToken()](#getToken--) | Returnerar en ny token bunden till denna [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returnerar true om avbrott begärts, annars false. |
| [interrupt()](#interrupt--) | Initierar begäran om avbrott. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```


Skapar en ny [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```


Returnerar en ny token bunden till denna [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Returnerar:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Returnerar true om avbrott begärts, annars false.

**Returnerar:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```


Initierar begäran om avbrott.