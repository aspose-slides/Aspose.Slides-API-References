---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: به شما امکان ایجاد بخش‌های آزمایشی را می‌دهد
type: docs
url: /fa/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

به شما امکان ایجاد بخش‌های آزمایشی را می‌دهد

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createPortion()](#createPortion--) | یک بخش متنی خالی ایجاد می‌کند. |
| [createPortion(String str)](#createPortion-java.lang.String-) | یک بخش متنی را از رشتهٔ مشخص شده ایجاد می‌کند. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | یک بخش را با استفاده از دادهٔ بخش مشخص شده ایجاد می‌کند. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


یک بخش متنی خالی ایجاد می‌کند.

**بازمی‌گرداند:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


یک بخش متنی را از رشتهٔ مشخص شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | java.lang.String | String. |

**بازمی‌گرداند:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


یک بخش را با استفاده از دادهٔ بخش مشخص شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | یک بخش برای استفاده. |

**بازمی‌گرداند:**
[IPortion](../../com.aspose.slides/iportion) - Portion.