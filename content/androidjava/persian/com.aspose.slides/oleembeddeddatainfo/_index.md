---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر اطلاعات داده توکار برای شی OLE.
type: docs
url: /fa/com.aspose.slides/oleembeddeddatainfo/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)  
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

نمایانگر اطلاعات داده‌های توکار برای شی OLE.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | یک نمونه جدید از اطلاعات داده توکار برای شی OLE ایجاد می‌کند. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | یک نمونه جدید از اطلاعات داده توکار برای شی OLE ایجاد می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | داده‌های فایل یک شی OLE توکار را بازمی‌گرداند فقط خواندنی byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | پسوند فایل برای شی OLE توکار فعلی را بازمی‌گرداند فقط خواندنی String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

یک نمونه جدید از اطلاعات داده توکار برای شی OLE ایجاد می‌کند.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

یک نمونه جدید از اطلاعات داده توکار برای شی OLE ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| embeddedFileData | byte[] | داده‌های فایل یک شی OLE توکار byte[]. |
| embeddedFileExtension | java.lang.String | پسوند فایل برای شی OLE توکار فعلی String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

داده‌های فایل یک شی OLE توکار را بازمی‌گرداند فقط خواندنی byte[].

**بازگشت:**  
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

پسوند فایل برای شی OLE توکار فعلی را بازمی‌گرداند فقط خواندنی String.

**بازگشت:**  
java.lang.String