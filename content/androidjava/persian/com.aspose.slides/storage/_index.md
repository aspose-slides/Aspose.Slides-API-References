---
title: Storage
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش دهندهٔ یک ذخیره‌سازی موقتی برای .
type: docs
url: /fa/com.aspose.slides/storage/
---
**ارث-بری:**  
java.lang.Object  
```
public final class Storage
```

نمایش دهندهٔ یک ذخیره‌سازی موقتی برای [WebDocument](../../com.aspose.slides/webdocument).

## سازنده‌ها

| سازنده | شرح |
| --- | --- |
| [Storage()](#Storage--) |  |

## متدها

| متد | شرح |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | مقدار را در ذخیره‌سازی قرار می‌دهد. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | داده را از ذخیره‌سازی دریافت می‌کند. |
| [containsKey(String key)](#containsKey-java.lang.String-) | تعیین می‌کند آیا ذخیره‌سازی عنصری با کلید مشخص‌شده دارد یا خیر. |

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
TValue - مقدار داده در صورت موجود بودن در مجموعه داده، null در غیر این صورت.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

تعیین می‌کند آیا ذخیره‌سازی عنصری با کلید مشخص‌شده دارد یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | java.lang.String | کلید مقدار. |

**بازگشت:**
boolean - در صورتی که ذخیره‌سازی عنصری با کلید مشخص‌شده داشته باشد true، در غیر این صورت false.