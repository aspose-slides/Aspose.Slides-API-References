---
title: IVbaProject
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهندهٔ پروژه VBA با ماکروهای ارائه.
type: docs
url: /fa/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

نمایش‌دهندهٔ پروژه VBA با ماکروهای ارائه.
## متدها

| Method | Description |
| --- | --- |
| [getName()](#getName--) | نام پروژه VBA را برمی‌گرداند. |
| [getModules()](#getModules--) | فهرست همه ماژول‌های موجود در پروژه VBA را برمی‌گرداند. |
| [getReferences()](#getReferences--) | فهرست همه مراجع موجود در پروژه VBA را برمی‌گرداند. |
| [toBinary()](#toBinary--) | نمایش باینری پروژه VBA به صورت OLE container را برمی‌گرداند. |
| [isPasswordProtected()](#isPasswordProtected--) | نشان می‌دهد آیا VBAProject با رمز عبور برای مشاهده خصوصیات پروژه محافظت شده است یا خیر. |
### getName() {#getName--}
```
public abstract String getName()
```


نام پروژه VBA را برمی‌گرداند. فقط-خواندنی String.

**بازگرداندن:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


فهرست همه ماژول‌های موجود در پروژه VBA را برمی‌گرداند. فقط-خواندنی [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**بازگرداندن:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


فهرست همه مراجع موجود در پروژه VBA را برمی‌گرداند. فقط-خواندنی [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**بازگرداندن:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


نمایش باینری پروژه VBA به صورت OLE container را برمی‌گرداند. فقط-خواندنی byte[].

**بازگرداندن:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


نشان می‌دهد آیا VBAProject با رمز عبور برای مشاهده خصوصیات پروژه محافظت شده است یا خیر. فقط-خواندنی boolean.

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

**بازگرداندن:**
boolean