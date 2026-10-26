---
title: TemplateContext
second_title: Aspose.Slides برای جاوا مرجع API
description: نمایانگر یک رابط شیء مدل برای یک موتور قالب است.
type: docs
url: /fa/com.aspose.slides/templatecontext/
---
**ارث-بری:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

نمایانگر یک رابط شیء مدل برای یک موتور قالب است.

## متدها

| متد | توضیح |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | یک زمینهٔ قالب فرزند ایجاد می‌کند. |
| [getObject()](#getObject--) | شیء مدل را برمی‌گرداند. |
| [getOutput()](#getOutput--) | مجموعه‌ای از عناصر خروجی سند میزبان را برمی‌گرداند. |
| [getLocal()](#getLocal--) | ذخیره‌سازی محلی زمینهٔ قالب فعلی را برمی‌گرداند. |
| [getGlobal()](#getGlobal--) | ذخیره‌سازی سراسری سند میزبان را برمی‌گرداند. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

یک زمینهٔ قالب فرزند ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subModel | TSubModel | شیء مدل فرزند. |

**بازگرداندن:**
[TemplateContext](../../com.aspose.slides/templatecontext) - زمینهٔ قالب جدید با مدل داده‌شده و مجموعهٔ خروجی مادر و ذخیره‌سازی سراسری.

### getObject() {#getObject--}
```
public final TObject getObject()
```

شیء مدل را برمی‌گرداند. فقط-خواندنی Object.

**بازگرداندن:**
TObject

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

مجموعه‌ای از عناصر خروجی سند میزبان را برمی‌گرداند. فقط-خواندنی [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**بازگرداندن:**
[Output](../../com.aspose.slides/output)

### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

ذخیره‌سازی محلی زمینهٔ قالب فعلی را برمی‌گرداند. فقط-خواندنی [Storage](../../com.aspose.slides/storage).

**بازگرداندن:**
[Storage](../../com.aspose.slides/storage)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

ذخیره‌سازی سراسری سند میزبان را برمی‌گرداند. فقط-خواندنی [Storage](../../com.aspose.slides/storage).

**بازگرداندن:**
[Storage](../../com.aspose.slides/storage)