---
title: Video
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر تصویری که در یک ارائه جاسازی شده است.
type: docs
url: /fa/com.aspose.slides/video/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

نمایانگر تصویری است که در یک ارائه جاسازی شده است.
## متدها

| متد | توضیح |
| --- | --- |
| [getContentType()](#getContentType--) | یک نوع MIME برای یک ویدیو را برمی‌گرداند، که در (\#getBinaryData.getBinaryData) کدگذاری شده است. |
| [getBinaryData()](#getBinaryData--) | یک کپی از داده‌های یک صدا را برمی‌گرداند. |
| [getStream()](#getStream--) | جریانی از نوع Stream برای خواندن را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

یک نوع MIME برای یک ویدیو را برمی‌گرداند، که در (\#getBinaryData.getBinaryData) کدگذاری شده است. رشتهٔ فقط-خواندنی.

**بازگرداندن:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

یک کپی از داده‌های یک صدا را برمی‌گرداند. در صورت مقدار بزرگ داده‌ها، استفاده از متد \#getStream.getStream را در نظر بگیرید تا از بارگذاری غیرضروری داده‌های ویدیو در حافظه یا حتی بروز خطای OutOfMemoryException جلوگیری شود. آرایه بایت فقط-خواندنی.

**بازگرداندن:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

جریانی از نوع Stream برای خواندن را برمی‌گرداند. پس از استفاده، از 'using' استفاده کنید یا جریان را ببندید.

**بازگرداندن:**
java.io.InputStream - جریان برای خواندن.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent\_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگرداندن:**
com.aspose.slides.IDOMObject