---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for classes which receive warning
type: docs
url: /id/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Antarmuka untuk kelas yang menerima peringatan
## Metode

| Metode | Deskripsi |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Metode callback yang menerima peringatan dan memutuskan apakah operasi harus dibatalkan. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Metode callback yang menerima peringatan dan memutuskan apakah operasi harus dibatalkan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Peringatan untuk diproses. |

**Returns:**
int - Keputusan penghentian [ReturnAction](../../com.aspose.slides/returnaction).