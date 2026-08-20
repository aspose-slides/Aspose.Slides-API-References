---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /th/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

อนุญาตให้สร้างโปรเจกต์ VBA ผ่านอินเทอร์เฟซ COM
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | สร้างโปรเจกต์ VBA ใหม่. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | อ่านโปรเจกต์ VBA จากคอนเทนเนอร์ OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


สร้างโปรเจกต์ VBA ใหม่.

**คืนค่า:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - โปรเจกต์ VBA ใหม่
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


อ่านโปรเจกต์ VBA จากคอนเทนเนอร์ OLE.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | ข้อมูล Ole byte[] |

**คืนค่า:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - โปรเจกต์ VBA ที่อ่าน