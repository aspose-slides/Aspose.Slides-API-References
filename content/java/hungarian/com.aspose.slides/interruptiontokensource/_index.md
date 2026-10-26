---
title: InterruptionTokenSource
second_title: Aspose.Slides for Java API Referencia
description: A forrását képviseli.
type: docs
url: /hu/com.aspose.slides/interruptiontokensource/
---
**Inheritance:**
java.lang.Object
```
public class InterruptionTokenSource
```

A [InterruptionToken](../../com.aspose.slides/interruptiontoken) forrását képviseli.
## Konstruktorok

| Constructor | Leírás |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | Létrehoz egy új [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource). |
## Metódusok

| Method | Leírás |
| --- | --- |
| [getToken()](#getToken--) | Új token visszaadása, amely ehhez a [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)-hez van kötve. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Igazat ad vissza, ha a megszakítás kért, egyébként hamisat. |
| [interrupt()](#interrupt--) | Megszakítási kérelem inicializálása. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```


Új [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)-t hoz létre.

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```


Új token visszaadása, amely ehhez a [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)-hez van kötve.

**Returns:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Igazat ad vissza, ha a megszakítás kért, egyébként hamisat.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```


Megszakítási kérelem inicializálása.