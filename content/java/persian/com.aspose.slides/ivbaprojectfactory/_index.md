---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: امکان ایجاد پروژه VBA از طریق رابط COM
type: docs
url: /fa/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

امکان ایجاد پروژه VBA از طریق رابط COM
## متدها

| متد | توضیح |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | یک پروژه VBA جدید ایجاد می‌کند. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | پروژه VBA را از مخزن OLE می‌خواند. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

یک پروژه VBA جدید ایجاد می‌کند.

**بازگشت:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - پروژه VBA جدید
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

پروژه VBA را از مخزن OLE می‌خواند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | داده Ole byte[] |

**بازگشت:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - پروژه VBA خوانده شده