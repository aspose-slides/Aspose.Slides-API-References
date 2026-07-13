---
title: InterruptionToken
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Kelas ini mewakili token yang digunakan untuk memberi sinyal pada tugas yang berjalan lama apakah interupsi diminta.
type: docs
url: /id/com.aspose.slides/interruptiontoken/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Kelas ini mewakili token yang digunakan untuk memberi sinyal pada tugas yang berjalan lama apakah interupsi diminta.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getNone()](#getNone--) | Mewakili token interupsi kosong. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Mengembalikan true jika interupsi diminta. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Melemparkan an jika interupsi diminta. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


Mewakili token interupsi kosong.

--------------------

Operasi yang berjalan lama tidak akan pernah diinterupsi melalui [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) saat menggunakan token ini.

**Mengembalikan:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Mengembalikan true jika interupsi diminta.

**Mengembalikan:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


Melemparkan an jika interupsi diminta.