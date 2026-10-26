---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: A forrását reprezentálja.
type: docs
url: /hu/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

A [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) forrását reprezentálja.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getToken()](#getToken--) | Új tokent ad vissza, amely ehhez a [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) kapcsolódik. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Igaz, ha megszakítás kérve van, egyébként hamis. |
| [interrupt()](#interrupt--) | Megszakítási kérést inicializálja. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Új tokent ad vissza, amely ehhez a [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) kapcsolódik.

**Visszaadja:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Igaz, ha megszakítás kérve van, egyébként hamis.

**Visszaadja:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Megszakítási kérést inicializálja.