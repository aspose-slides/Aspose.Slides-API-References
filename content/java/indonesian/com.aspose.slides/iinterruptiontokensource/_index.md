---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Represents the source of .
type: docs
url: /id/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Mewakili sumber [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getToken()](#getToken--) | Mengembalikan token baru yang terikat pada [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) ini. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Mengembalikan true jika interupsi diminta, false sebaliknya. |
| [interrupt()](#interrupt--) | Menginisialisasi permintaan interupsi. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Mengembalikan token baru yang terikat pada [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) ini.

**Mengembalikan:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Mengembalikan true jika interupsi diminta, false sebaliknya.

**Mengembalikan:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Menginisialisasi permintaan interupsi.