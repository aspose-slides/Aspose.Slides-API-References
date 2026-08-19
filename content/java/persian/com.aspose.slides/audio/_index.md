---
title: Audio
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک فایل صوتی توکار است.
type: docs
url: /fa/com.aspose.slides/audio/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

نمایانگر یک فایل صوتی توکار است.
## روش‌ها

| روش | توضیح |
| --- | --- |
| [getContentType()](#getContentType--) | یک نوع MIME برای صوت را برمی‌گرداند که در (\#getBinaryData.getBinaryData) کدگذاری شده است. |
| [setContentType(String value)](#setContentType-java.lang.String-) | یک نوع MIME برای صوت را برمی‌گرداند که در (\#getBinaryData.getBinaryData) کدگذاری شده است. |
| [getBinaryData()](#getBinaryData--) | کپی داده‌های صوت را برمی‌گرداند. |
| [getStream()](#getStream--) | یک Stream برای خواندن برمی‌گرداند. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


یک نوع MIME برای صوت را برمی‌گرداند که در (\#getBinaryData.getBinaryData) کدگذاری شده است. رشته فقط خواندنی.

**بازگرداندن:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


یک نوع MIME برای صوت را برمی‌گرداند که در (\#getBinaryData.getBinaryData) کدگذاری شده است. رشته فقط خواندنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


کپی داده‌های صوت را برمی‌گرداند. در صورت وجود حجم زیاد داده‌ها، استفاده از متد \#getStream.getStream توصیه می‌شود تا از بارگذاری غیرضروری داده‌های صوت در حافظه یا حتی بروز OutOfMemoryException جلوگیری شود. آرایه byte[] فقط خواندنی.

**بازگرداندن:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


یک Stream برای خواندن برمی‌گرداند. پس از استفاده، از 'using' استفاده کنید یا استریم را ببندید.

**بازگرداندن:**
java.io.InputStream - Stream برای خواندن.