---
title: TemplateContext
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک رابط شی مدل برای یک موتور قالب است.
type: docs
url: /fa/com.aspose.slides/templatecontext/
---
**ارث‌بری:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

نمایانگر یک رابط شی مدل برای یک موتور قالب.

## متدها

| متد | توضیح |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Creates a child template context. |
| [getObject()](#getObject--) | Returns the model object. |
| [getOutput()](#getOutput--) | Returns collection of output elements of the host document. |
| [getLocal()](#getLocal--) | Returns local storage of the current template context. |
| [getGlobal()](#getGlobal--) | Returns global storage of the host document. |

### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


یک زمینه الگو فرزند ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| subModel | TSubModel | Child model object. |

**بازگشت:**
[TemplateContext](../../com.aspose.slides/templatecontext) - زمینه الگو جدید با مدل داده‌شده و مجموعه خروجی والد و ذخیره‌سازی سراسری.

### getObject() {#getObject--}
```
public final TObject getObject()
```


شی مدل را باز می‌گرداند. فقط-خواندنی Object.

**بازگشت:**
TObject

### getOutput() {#getOutput--}
```
public final Output getOutput()
```


مجموعه‌ای از عناصر خروجی سند میزبان را باز می‌گرداند. فقط-خواندنی [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**بازگشت:**
[Output](../../com.aspose.slides/output)

### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


ذخیره‌سازی محلی زمینه الگو کنونی را باز می‌گرداند. فقط-خواندنی [Storage](../../com.aspose.slides/storage).

**بازگشت:**
[Storage](../../com.aspose.slides/storage)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


ذخیره‌سازی سراسری سند میزبان را باز می‌گرداند. فقط-خواندنی [Storage](../../com.aspose.slides/storage).

**بازگشت:**
[Storage](../../com.aspose.slides/storage)