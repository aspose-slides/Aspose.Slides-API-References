---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /id/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Mewakili antarmuka dasar untuk semua peringatan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | If receiver is not null ends warning to a specified receiver and throws the AbortRequestedException if receiver decided to abort a operation. |
| [getWarningType()](#getWarningType--) | Returns a type of warning. |
| [getDescription()](#getDescription--) | Returns a human readable description of this warning. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Jika receiver tidak null, mengakhiri peringatan ke receiver yang ditentukan dan melempar AbortRequestedException jika receiver memutuskan untuk membatalkan operasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Objek receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Mengembalikan tipe peringatan. Hanya-baca [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Mengembalikan:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Mengembalikan deskripsi yang dapat dibaca manusia dari peringatan ini. Hanya-baca String.

**Mengembalikan:**
java.lang.String