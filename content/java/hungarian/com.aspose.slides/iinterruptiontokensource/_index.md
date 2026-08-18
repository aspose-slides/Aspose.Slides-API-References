---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: A forrását képviseli.
type: docs
url: /hu/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

A [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) forrását képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [getToken()](#getToken--) | Új tokent ad vissza, amely ehhez a [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)-hez van kapcsolva. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Igazat ad, ha a megszakítás kérve van, egyébként hamis. |
| [interrupt()](#interrupt--) | Inicializálja a megszakítás kérését. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Új tokent ad vissza, amely ehhez a [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)-hez van kapcsolva.

**Visszatér:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Igazat ad, ha a megszakítás kérve van, egyébként hamis.

**Visszatér:**  
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Inicializálja a megszakítás kérését.