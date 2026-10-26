---
title: VbaProject
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงโครงการ VBA ที่มีมาโครในการนำเสนอ.
type: docs
url: /th/com.aspose.slides/vbaproject/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

แสดงถึงโครงการ VBA ที่มีมาโครการนำเสนอ.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [VbaProject()](#VbaProject--) | คอนสตรัคเตอร์นี้สร้างโครงการ VBA ใหม่ตั้งแต่เริ่มต้น |
| [VbaProject(byte[] data)](#VbaProject-byte---) | คอนสตรัคเตอร์นี้โหลดโครงการ VBA จากการแสดงผลไบนารีของคอนเทนเนอร์ OLE |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | คืนค่าชื่อของโครงการ VBA |
| [getModules()](#getModules--) | คืนค่ารายการของโมดูลทั้งหมดที่อยู่ในโครงการ VBA |
| [getReferences()](#getReferences--) | คืนค่ารายการของการอ้างอิงทั้งหมดที่อยู่ในโครงการ VBA |
| [toBinary()](#toBinary--) | คืนค่าการแสดงผลไบนารีของโครงการ VBA เป็นคอนเทนเนอร์ OLE |
| [isPasswordProtected()](#isPasswordProtected--) | ระบุว่า VBAProject ถูกป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติของโครงการหรือไม่ |

### VbaProject() {#VbaProject--}
```
public VbaProject()
```

คอนสตรัคเตอร์นี้สร้างโครงการ VBA ใหม่ตั้งแต่เริ่มต้น โครงการจะถูกสร้างใน 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

คอนสตรัคเตอร์นี้โหลดโครงการ VBA จากการแสดงผลไบนารีของคอนเทนเนอร์ OLE

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

คืนค่าชื่อของโครงการ VBA. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

คืนค่ารายการของโมดูลทั้งหมดที่อยู่ในโครงการ VBA. อ่านอย่างเดียว [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**คืนค่า:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

คืนค่ารายการของการอ้างอิงทั้งหมดที่อยู่ในโครงการ VBA. อ่านอย่างเดียว [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**คืนค่า:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

คืนค่าการแสดงผลไบนารีของโครงการ VBA เป็นคอนเทนเนอร์ OLE

**คืนค่า:**
byte[] - การแสดงผลไบนารีของโครงการ VBA เป็นคอนเทนเนอร์ OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

ระบุว่า VBAProject ถูกป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติของโครงการหรือไม่. อ่านอย่างเดียว boolean .

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


**คืนค่า:**
boolean