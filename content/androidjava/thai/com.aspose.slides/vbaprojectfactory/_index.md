---
title: VbaProjectFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อนุญาตให้สร้างโปรเจค VBA ผ่านอินเทอร์เฟซ COM
type: docs
url: /th/com.aspose.slides/vbaprojectfactory/
---
**สืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

อนุญาตให้สร้างโปรเจค VBA ผ่านอินเทอร์เฟซ COM
## คอนสตรักเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project factory static instance. |
| [createVbaProject()](#createVbaProject--) | Creates new VBA project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```

### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```

VBA project factory static instance. อ่านอย่างเดียว [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**คืนค่า:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```

Creates new VBA project.

**คืนค่า:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - New VBA project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```

Reads VBA project from OLE container.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | byte[] |  |

**คืนค่า:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Read VBA project