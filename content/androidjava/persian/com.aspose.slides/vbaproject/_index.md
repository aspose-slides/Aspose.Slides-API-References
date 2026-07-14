---
title: VbaProject
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایشگر پروژه VBA همراه با ماکروهای ارائه.
type: docs
url: /fa/com.aspose.slides/vbaproject/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

نمایشگر پروژه VBA همراه با ماکروهای ارائه.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [VbaProject()](#VbaProject--) | این سازنده یک پروژه VBA جدید از ابتدا ایجاد می‌کند. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | این سازنده پروژه VBA را از نمای باینری کانتینر OLE بارگذاری می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام پروژه VBA را برمی‌گرداند. |
| [getModules()](#getModules--) | فهرست تمام ماژول‌های موجود در پروژه VBA را برمی‌گرداند. |
| [getReferences()](#getReferences--) | فهرست تمام ارجاعات موجود در پروژه VBA را برمی‌گرداند. |
| [toBinary()](#toBinary--) | نمای باینری پروژه VBA به عنوان کانتینر OLE را برمی‌گرداند |
| [isPasswordProtected()](#isPasswordProtected--) | نشان می‌دهد آیا VBAProject توسط رمز عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا خیر. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

این سازنده یک پروژه VBA جدید از ابتدا ایجاد می‌کند. پروژه در کد صفحه 1252 Windows Latin 1 (ANSI) ساخته خواهد شد

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

این سازنده پروژه VBA را از نمای باینری کانتینر OLE بارگذاری می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

نام پروژه VBA را برمی‌گرداند. فقط-خواندنی String.

**برمی‌گرداند:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

فهرست تمام ماژول‌های موجود در پروژه VBA را برمی‌گرداند. فقط-خواندنی [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**برمی‌گرداند:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

فهرست تمام ارجاعات موجود در پروژه VBA را برمی‌گرداند. فقط-خواندنی [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**برمی‌گرداند:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

نمایش باینری پروژه VBA به عنوان کانتینر OLE را برمی‌گرداند

**برمی‌گرداند:**
byte[] - نمای باینری پروژه VBA به عنوان کانتینر OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

نشان می‌دهد آیا VBAProject توسط رمز عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا خیر. فقط-خواندنی boolean .

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

**برمی‌گرداند:**
boolean