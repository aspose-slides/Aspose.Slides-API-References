---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /th/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Allows to create VBA project via COM interface
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | สร้าง VBA project ใหม่. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | อ่าน VBA project จากคอนเทนเนอร์ OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

สร้าง VBA project ใหม่.

**ผลลัพธ์:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - VBA project ใหม่
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

อ่าน VBA project จากคอนเทนเนอร์ OLE.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**ผลลัพธ์:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - อ่าน VBA project