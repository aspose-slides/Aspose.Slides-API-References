---
title: IVbaProject
second_title: Aspose.Slides for Java مستندات API
description: نمایانگر پروژه VBA با ماکروهای ارائه.
type: docs
url: /fa/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

نمایانگر پروژه VBA با ماکروهای ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام پروژه VBA را برمی‌گرداند. |
| [getModules()](#getModules--) | لیست تمام ماژول‌های موجود در پروژه VBA را برمی‌گرداند. |
| [getReferences()](#getReferences--) | لیست تمام مراجع موجود در پروژه VBA را برمی‌گرداند. |
| [toBinary()](#toBinary--) | نمایش باینری پروژه VBA را به‌صورت مخزن OLE برمی‌گرداند. |
| [isPasswordProtected()](#isPasswordProtected--) | نشان می‌دهد آیا VBAProject با کلمه عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا نه. |
### getName() {#getName--}
```
public abstract String getName()
```


نام پروژه VBA را برمی‌گرداند. فقط‌خواندنی String.

**باز می‌گرداند:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


لیست تمام ماژول‌های موجود در پروژه VBA را برمی‌گرداند. فقط‌خواندنی [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**باز می‌گرداند:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


لیست تمام مراجع موجود در پروژه VBA را برمی‌گرداند. فقط‌خواندنی [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**باز می‌گرداند:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


نمایش باینری پروژه VBA را به‌صورت مخزن OLE برمی‌گرداند. فقط‌خواندنی byte[].

**باز می‌گرداند:**
byte[] - نمایش باینری پروژه VBA به‌صورت مخزن OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


نشان می‌دهد آیا VBAProject با کلمه عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا نه. فقط‌خواندنی boolean.

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


**باز می‌گرداند:**
boolean