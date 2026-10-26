---
title: PortionFactory
second_title: Aspose.Slides برای مرجع API جاوا
description: اجازه می‌دهد قسمت‌های آزمایشی ایجاد کند
type: docs
url: /fa/com.aspose.slides/portionfactory/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

اجازه می‌دهد قسمت‌های آزمایشی ایجاد کند

--------------------

برای سازگاری COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


یک قسمت متنی خالی ایجاد می‌کند.

**بازگشت:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


یک قسمت متنی را از رشته‌ی مشخص‌شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | java.lang.String | String. |

**بازگشت:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


یک قسمت را با استفاده از داده‌های یک قسمت مشخص ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | یک قسمت برای استفاده. |

**بازگشت:**
[IPortion](../../com.aspose.slides/iportion) - Portion.