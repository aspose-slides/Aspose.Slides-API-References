---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: Kelas ini mewakili token yang digunakan untuk memberi sinyal pada tugas yang berjalan lama apakah interupsi telah diminta.
type: docs
url: /id/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Kelas ini mewakili token yang digunakan untuk memberi sinyal pada tugas yang berjalan lama apakah interupsi telah diminta.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Mengembalikan true jika interupsi diminta. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Melemparkan an jika interupsi diminta. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Mengembalikan true jika interupsi diminta.

**Mengembalikan:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Melemparkan an jika interupsi diminta.