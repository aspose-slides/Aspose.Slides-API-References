---
title: OleEmbeddedDataInfo
second_title: مرجع API Aspose.Slides برای Java
description: اطلاعات دادهٔ جاساز برای شی OLE را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/oleembeddeddatainfo/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

اطلاعات دادهٔ جاساز برای شی OLE را نشان می‌دهد.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | یک اطلاعات دادهٔ جاساز جدید برای شی OLE ایجاد می‌کند. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | یک نمونهٔ جدید از اطلاعات دادهٔ جاساز برای شی OLE ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | دادهٔ فایل شی OLE جاساز را برمی‌گرداند؛ فقط-خواندنی byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | پسوند فایل شی OLE جاساز جاری را برمی‌گرداند؛ فقط-خواندنی String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


یک اطلاعات دادهٔ جاساز جدید برای شی OLE ایجاد می‌کند.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


یک نمونهٔ جدید از اطلاعات دادهٔ جاساز برای شی OLE ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| embeddedFileData | byte[] | دادهٔ فایل شی OLE جاساز byte[]. |
| embeddedFileExtension | java.lang.String | پسوند فایل شی OLE جاساز جاری String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


دادهٔ فایل شی OLE جاساز را برمی‌گرداند؛ فقط-خواندنی byte[].

**برگشت:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


پسوند فایل شی OLE جاساز جاری را برمی‌گرداند؛ فقط-خواندنی String.

**برگشت:**
java.lang.String