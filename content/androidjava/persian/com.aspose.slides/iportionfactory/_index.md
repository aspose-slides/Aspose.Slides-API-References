---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: اجازه می‌دهد تا بخش‌های تست ایجاد شود
type: docs
url: /fa/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

اجازه می‌دهد تا بخش‌های تست ایجاد شود

--------------------

برای سازگاری با COM
## متدها

| متد | توضیح |
| --- | --- |
| [createPortion()](#createPortion--) | یک بخش متنی خالی ایجاد می‌کند. |
| [createPortion(String str)](#createPortion-java.lang.String-) | یک بخش متنی از رشته مشخص شده ایجاد می‌کند. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | یک بخش را با استفاده از داده‌های بخش مشخص شده ایجاد می‌کند. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


یک بخش متنی خالی ایجاد می‌کند.

**باز می‌گردد:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


یک بخش متنی از رشته مشخص شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | java.lang.String | String. |

**باز می‌گردد:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


یک بخش را با استفاده از داده‌های بخش مشخص شده ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | یک portion برای استفاده. |

**باز می‌گردد:**
[IPortion](../../com.aspose.slides/iportion) - Portion.