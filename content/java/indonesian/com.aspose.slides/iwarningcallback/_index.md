---
title: IWarningCallback
second_title: Aspose.Slides untuk Referensi API Java
description: Antarmuka untuk kelas yang menerima peringatan
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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Peringatan untuk diproses. |

**Mengembalikan:**
int - Keputusan pembatalan [ReturnAction](../../com.aspose.slides/returnaction).