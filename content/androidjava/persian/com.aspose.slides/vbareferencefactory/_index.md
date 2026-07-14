---
title: VbaReferenceFactory
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: اجازه می‌دهد تا مراجع پروژه VBA را از طریق رابط COM ایجاد کند
type: docs
url: /fa/com.aspose.slides/vbareferencefactory/
---
**ارث‌بری:**
java.lang.Object

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

اجازه می‌دهد تا مراجع پروژه VBA را از طریق رابط COM ایجاد کند
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getInstance()](#getInstance--) | نمونهٔ استاتیک کارخانه مراجع پروژه VBA |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | یک مرجع کتابخانه نوع OLE Automation جدید ایجاد می‌کند |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


نمونهٔ استاتیک کارخانه مراجع پروژه VBA. فقط‌خواندنی [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**باز می‌گردد:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


یک مرجع کتابخانه نوع OLE Automation جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**باز می‌گردد:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - مرجع کتابخانه نوع OLE Automation جدید