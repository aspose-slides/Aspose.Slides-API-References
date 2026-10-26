---
title: VbaProjectFactory
second_title: Aspose.Slides برای اندروید از طریق مستندات API جاوا
description: اجازه می‌دهد پروژه VBA را از طریق رابط COM ایجاد کند
type: docs
url: /fa/com.aspose.slides/vbaprojectfactory/
---
**وراثت:**  
java.lang.Object

**همهٔ رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)  
```
public class VbaProjectFactory implements IVbaProjectFactory
```

اجازه می‌دهد پروژه VBA را از طریق رابط COM ایجاد کند
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getInstance()](#getInstance--) | نمونهٔ ثابت کارخانهٔ پروژه VBA. |
| [createVbaProject()](#createVbaProject--) | پروژهٔ جدید VBA را ایجاد می‌کند. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | پروژه VBA را از محفظه OLE می‌خواند. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```

### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```

نمونهٔ ثابت کارخانهٔ پروژه VBA. فقط-خواندنی [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**بازگرداندن:**  
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```

پروژهٔ جدید VBA را ایجاد می‌کند.

**بازگرداندن:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - پروژه جدید VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```

پروژه VBA را از محفظه OLE می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] |  |

**بازگرداندن:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - پروژه VBA خوانده شده