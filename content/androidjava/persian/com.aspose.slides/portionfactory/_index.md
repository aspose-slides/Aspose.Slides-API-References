---
title: PortionFactory
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: اجازه ایجاد بخش‌های آزمایشی را می‌دهد
type: docs
url: /fa/com.aspose.slides/portionfactory/
---
**وراثت:**  
java.lang.Object

**همهٔ رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)  
```
public class PortionFactory implements IPortionFactory
```

اجازه ایجاد بخش‌های آزمایشی را می‌دهد

--------------------

برای سازگاری با COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createPortion()](#createPortion--) | یک بخش متن خالی را ایجاد می‌کند. |
| [createPortion(String str)](#createPortion-java.lang.String-) | یک بخش متن را از رشتهٔ مشخص‌شده ایجاد می‌کند. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | یک بخش را با استفاده از دادهٔ بخش مشخص‌شده ایجاد می‌کند. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

یک بخش متن خالی را ایجاد می‌کند.

**برگشت:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

یک بخش متن را از رشتهٔ مشخص‌شده ایجاد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | java.lang.String | رشته. |

**برگشت:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

یک بخش را با استفاده از دادهٔ بخش مشخص‌شده ایجاد می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | یک بخش برای استفاده. |

**برگشت:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.