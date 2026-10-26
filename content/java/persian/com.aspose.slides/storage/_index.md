---
title: Storage
second_title: مرجع API Aspose.Slides برای Java
description: نمایندهٔ یک ذخیره‌سازی موقت داده برای .
type: docs
url: /fa/com.aspose.slides/storage/
---
**ارث‌بری:**
java.lang.Object
```
public final class Storage
```

نمایندهٔ یک ذخیره‌سازی موقت داده برای [WebDocument](../../com.aspose.slides/webdocument).
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Storage()](#Storage--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | مقدار را در ذخیره‌سازی قرار می‌دهد. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | داده را از ذخیره‌سازی دریافت می‌کند. |
| [containsKey(String key)](#containsKey-java.lang.String-) | تعیین می‌کند آیا ذخیره‌سازی عنصری با کلید مشخص دارد یا خیر. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


مقدار را در ذخیره‌سازی قرار می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | java.lang.String | کلید برای مقدار. |
| value | TValue | مقدار. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


داده را از ذخیره‌سازی دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | java.lang.String | کلید مقدار. |

**بازگشت:**
TValue - مقدار داده اگر در مجموعه داده موجود باشد، در غیر این صورت null.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


تعیین می‌کند آیا ذخیره‌سازی عنصری با کلید مشخص دارد یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | java.lang.String | کلید مقدار. |

**بازگشت:**
boolean - True اگر ذخیره‌سازی عنصری با کلید مشخص دارد، در غیر این صورت false.