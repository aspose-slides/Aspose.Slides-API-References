---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Represents the source of .
type: docs
url: /cs/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Představuje zdroj [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Metody

| Method | Description |
| --- | --- |
| [getToken()](#getToken--) | Vrací nový token vázaný k tomuto [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Vrací true, pokud je přerušení požadováno, jinak false. |
| [interrupt()](#interrupt--) | Inicializuje žádost o přerušení. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Vrací nový token vázaný k tomuto [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Vrací:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Vrací true, pokud je přerušení požadováno, jinak false.

**Vrací:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Inicializuje žádost o přerušení.