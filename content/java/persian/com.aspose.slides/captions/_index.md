---
title: Captions
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر زیرنویس‌های بسته WebVTT.
type: docs
url: /fa/com.aspose.slides/captions/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

نمایش زیرنویس‌های بسته WebVTT.
## متدها

| متد | توضیح |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | شناسهٔ یکتا (GUID) سراسری زیرنویس‌های بسته را بازمی‌گرداند. |
| [getLabel()](#getLabel--) | برچسب زیرنویس‌های بسته را بازمی‌گرداند یا تنظیم می‌کند. |
| [setLabel(String value)](#setLabel-java.lang.String-) | برچسب زیرنویس‌های بسته را بازمی‌گرداند یا تنظیم می‌کند. |
| [getBinaryData()](#getBinaryData--) | داده‌های باینری زیرنویس‌های بسته را بازمی‌گرداند. |
| [getDataAsString()](#getDataAsString--) | داده‌های زیرنویس بسته را به‌عنوان رشتهٔ کدگذاری‌شده UTF-8 بازمی‌گرداند. رشته فقط-خواندنی. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


شناسهٔ یکتا (GUID) سراسری زیرنویس‌های بسته را بازمی‌گرداند. فقط-خواندنی java.util.UUID.

**بازگشت:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


برچسب زیرنویس‌های بسته را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن رشته.

**بازگشت:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


برچسب زیرنویس‌های بسته را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن رشته.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


داده‌های باینری زیرنویس‌های بسته را بازمی‌گرداند. فقط-خواندنی byte[] .

**بازگشت:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


داده‌های زیرنویس بسته را به‌عنوان رشتهٔ کدگذاری‌شده UTF-8 بازمی‌گرداند. رشته فقط-خواندنی.

**بازگشت:**
java.lang.String