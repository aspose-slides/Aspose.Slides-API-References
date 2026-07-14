---
title: Audio
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
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

## متدها

| متد | توضیح |
| --- | --- |
| [getContentType()](#getContentType--) | یک نوع MIME از یک فایل صوتی را برمی‌گرداند، که در (\#getBinaryData.getBinaryData) کدگذاری شده است. |
| [setContentType(String value)](#setContentType-java.lang.String-) | یک نوع MIME از یک فایل صوتی را برمی‌گرداند، که در (\#getBinaryData.getBinaryData) کدگذاری شده است. |
| [getBinaryData()](#getBinaryData--) | کپی داده‌های یک فایل صوتی را برمی‌گرداند. |
| [getStream()](#getStream--) | یک Stream برای خواندن برمی‌گرداند. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

یک نوع MIME از یک فایل صوتی را برمی‌گرداند، که در (\#getBinaryData.getBinaryData) کدگذاری شده است. رشته فقط-خواندنی.

**بازگشت:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

یک نوع MIME از یک فایل صوتی را برمی‌گرداند، که در (\#getBinaryData.getBinaryData) کدگذاری شده است. رشته فقط-خواندنی.

**پارامترها:**

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

کپی داده‌های یک فایل صوتی را برمی‌گرداند. در صورت مقدار زیاد داده‌ها، استفاده از متد \#getStream.getStream را در نظر بگیرید تا از بارگذاری غیرضروری داده‌های صوتی در حافظه یا حتی بروز OutOfMemoryException جلوگیری شود. بایت[] فقط-خواندنی.

**بازگشت:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

یک Stream برای خواندن برمی‌گرداند. از 'using' استفاده کنید یا پس از استفاده، Stream را بسته کنید.

**بازگشت:**  
java.io.InputStream - Stream برای خواندن.