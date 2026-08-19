---
title: VbaProjectFactory
second_title: Aspose.Slides برای مرجع API جاوا
description: به شما امکان ایجاد پروژه VBA از طریق رابط COM را می‌دهد
type: docs
url: /fa/com.aspose.slides/vbaprojectfactory/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

به شما امکان ایجاد پروژه VBA از طریق رابط COM را می‌دهد
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project factory نمونهٔ ایستا. |
| [createVbaProject()](#createVbaProject--) | پروژهٔ جدید VBA را ایجاد می‌کند. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | پروژهٔ VBA را از کانتینر OLE می‌خواند. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```

### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```

VBA project factory نمونهٔ ایستا. فقط-خواندنی [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**بازگرداندن:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```

پروژهٔ جدید VBA را ایجاد می‌کند.

**بازگرداندن:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - پروژهٔ جدید VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```

پروژهٔ VBA را از کانتینر OLE می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] |  |

**بازگرداندن:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - پروژهٔ VBA خوانده‌شده