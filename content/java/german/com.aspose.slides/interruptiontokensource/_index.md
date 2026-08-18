---
title: InterruptionTokenSource
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Quelle von .
type: docs
url: /de/com.aspose.slides/interruptiontokensource/
---
**Vererbung:**
java.lang.Object
```
public class InterruptionTokenSource
```

Stellt die Quelle von [InterruptionToken](../../com.aspose.slides/interruptiontoken) dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | Erstellt ein neues [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getToken()](#getToken--) | Gibt ein neues Token zurück, das an dieses [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) gebunden ist. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Gibt true zurück, wenn eine Unterbrechung angefordert wurde, andernfalls false. |
| [interrupt()](#interrupt--) | Initialisiert eine Anfrage für eine Unterbrechung. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

Erstellt ein neues [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

Gibt ein neues Token zurück, das an dieses [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) gebunden ist.

**Rückgabewert:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Gibt true zurück, wenn eine Unterbrechung angefordert wurde, andernfalls false.

**Rückgabewert:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```

Initialisiert eine Anfrage für eine Unterbrechung.