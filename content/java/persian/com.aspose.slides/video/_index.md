---
title: Video
second_title: مرجع API Aspose.Slides برای Java
description: یک تصویر جاسازی‌شده در ارائه را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/video/
---
**ارث بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

یک تصویر جاسازی‌شده در ارائه را نشان می‌دهد.

## متدها

| متد | توضیحات |
| --- | --- |
| [getContentType()](#getContentType--) | MIME نوع یک ویدیو را باز می‌گرداند، کدگذاری شده در (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | کپی داده‌های یک صدا را باز می‌گرداند. |
| [getStream()](#getStream--) | جریان Stream را برای خواندن باز می‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

MIME نوع یک ویدیو را باز می‌گرداند، کدگذاری شده در (\#getBinaryData.getBinaryData). رشته فقط-خواندنی.

**باز می‌گردد:**  
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

کپی داده‌های یک صدا را باز می‌گرداند. در صورت حجم زیاد داده‌ها، استفاده از متد \#getStream.getStream را در نظر بگیرید تا از بارگذاری غیرضروری داده‌های ویدیو در حافظه یا حتی بروز OutOfMemoryException جلوگیری شود. byte[] فقط-خواندنی.

**باز می‌گردد:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

جریان Stream را برای خواندن باز می‌گرداند. از 'using' استفاده کنید یا پس از استفاده جریان را ببندید.

**باز می‌گردد:**  
java.io.InputStream - جریان برای خواندن.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را باز می‌گرداند. IDOMObject فقط-خواندنی.

**باز می‌گردد:**  
com.aspose.slides.IDOMObject