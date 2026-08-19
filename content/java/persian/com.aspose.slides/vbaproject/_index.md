---
title: VbaProject
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر پروژه VBA با ماکروهای ارائه.
type: docs
url: /fa/com.aspose.slides/vbaproject/
---
**وارثی:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

نمایانگر پروژه VBA با ماکروهای ارائه.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [VbaProject()](#VbaProject--) | این سازنده یک پروژه VBA جدید را از ابتدا ایجاد می‌کند. پروژه در صفحه‌کد 1252 Windows Latin 1 (ANSI) ایجاد خواهد شد |
| [VbaProject(byte[] data)](#VbaProject-byte---) | این سازنده پروژه VBA را از نمایش باینری کانتینر OLE بارگذاری می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام پروژه VBA را برمی‌گرداند. |
| [getModules()](#getModules--) | فهرست همه ماژول‌های موجود در پروژه VBA را برمی‌گرداند. |
| [getReferences()](#getReferences--) | فهرست همه ارجاعات موجود در پروژه VBA را برمی‌گرداند. |
| [toBinary()](#toBinary--) | نمایش باینری پروژه VBA به‌عنوان کانتینر OLE را برمی‌گرداند |
| [isPasswordProtected()](#isPasswordProtected--) | مشخص می‌کند آیا VBAProject با رمز عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا نه. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

این سازنده یک پروژه VBA جدید را از ابتدا ایجاد می‌کند. پروژه در صفحه‌کد 1252 Windows Latin 1 (ANSI) ایجاد خواهد شد

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

این سازنده پروژه VBA را از نمایش باینری کانتینر OLE بارگذاری می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

نام پروژه VBA را برمی‌گرداند. فقط‌خواندنی String.

**بازمی‌گرداند:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

فهرست همه ماژول‌های موجود در پروژه VBA را برمی‌گرداند. فقط‌خواندنی [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**بازمی‌گرداند:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

فهرست همه ارجاعات موجود در پروژه VBA را برمی‌گرداند. فقط‌خواندنی [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**بازمی‌گرداند:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

نمایش باینری پروژه VBA به‌عنوان کانتینر OLE را برمی‌گرداند

**بازمی‌گرداند:**
byte[] - نمایش باینری پروژه VBA به‌عنوان کانتینر OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

مشخص می‌کند آیا VBAProject با رمز عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا نه. فقط‌خواندنی boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازمی‌گرداند:**
boolean