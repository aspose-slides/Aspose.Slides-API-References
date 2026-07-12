---
title: InterruptionTokenSource
second_title: Aspose.Slides Androidra a Java API hivatkozáson keresztül
description: A forrását képviseli.
type: docs
url: /hu/com.aspose.slides/interruptiontokensource/
---
**Öröklés:**
java.lang.Object
```
public class InterruptionTokenSource
```

A(z) [InterruptionToken](../../com.aspose.slides/interruptiontoken) forrását képviseli.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | Létrehoz egy új [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource). |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getToken()](#getToken--) | Visszaad egy új token-t, amely ehhez a [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)-hez kötődik. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Visszaad true értéket, ha megszakítás kérve van, egyébként false. |
| [interrupt()](#interrupt--) | Inicializálja a megszakítás kérését. |

### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

Létrehoz egy új [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

Visszaad egy új token-t, amely ehhez a [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)-hez kötődik.

**Visszatér:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)

### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Visszaad true értéket, ha megszakítás kérve van, egyébként false.

**Visszatér:**
boolean

### interrupt() {#interrupt--}
```
public final void interrupt()
```

Inicializálja a megszakítás kérését.