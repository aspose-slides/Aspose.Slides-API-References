---
title: IInterruptionTokenSource
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili sumber dari .
type: docs
url: /id/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Mewakili sumber dari [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getToken()](#getToken--) | Mengembalikan token baru yang terikat ke [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) ini. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Mengembalikan true jika interupsi diminta, false sebaliknya. |
| [interrupt()](#interrupt--) | Inisialisasi permintaan interupsi. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Mengembalikan token baru yang terikat ke [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) ini.

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

Inisialisasi permintaan interupsi.