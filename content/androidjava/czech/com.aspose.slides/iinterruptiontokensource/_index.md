---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Representuje zdroj.
type: docs
url: /cs/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Representuje zdroj [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Methods

| Metoda | Popis |
| --- | --- |
| [getToken()](#getToken--) | Vrací nový token svázaný s tímto [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Vrací true, pokud je požadováno přerušení, jinak false. |
| [interrupt()](#interrupt--) | Inicializuje požadavek na přerušení. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Vrací nový token svázaný s tímto [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Návratová hodnota:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Vrací true, pokud je požadováno přerušení, jinak false.

**Návratová hodnota:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Inicializuje požadavek na přerušení.