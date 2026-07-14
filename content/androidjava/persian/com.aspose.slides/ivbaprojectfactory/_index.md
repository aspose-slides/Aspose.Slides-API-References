---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: اجازه می‌دهد پروژه VBA از طریق رابط COM ایجاد شود
type: docs
url: /fa/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

اجازه می‌دهد پروژه VBA از طریق رابط COM ایجاد شود
## Methods

| Method | Description |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | پروژه VBA جدید را ایجاد می‌کند. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | پروژه VBA را از مخزن OLE می‌خواند. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

پروژه VBA جدید را ایجاد می‌کند.

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