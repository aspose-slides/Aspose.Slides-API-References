---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Mewakili antarmuka dasar untuk semua peringatan.
type: docs
url: /id/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Mewakili antarmuka dasar untuk semua peringatan.
## Methods

| Method | Description |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Jika receiver tidak null, mengakhiri peringatan ke receiver yang ditentukan dan melempar AbortRequestedException jika receiver memutuskan untuk membatalkan operasi. |
| [getWarningType()](#getWarningType--) | Mengembalikan jenis peringatan. |
| [getDescription()](#getDescription--) | Mengembalikan deskripsi yang dapat dibaca manusia untuk peringatan ini. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


Jika receiver tidak null, mengakhiri peringatan ke receiver yang ditentukan dan melempar AbortRequestedException jika receiver memutuskan untuk membatalkan operasi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Objek receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


Mengembalikan jenis peringatan. Hanya-baca [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Mengembalikan:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Mengembalikan deskripsi yang dapat dibaca manusia untuk peringatan ini. Hanya-baca String.

**Mengembalikan:**
java.lang.String