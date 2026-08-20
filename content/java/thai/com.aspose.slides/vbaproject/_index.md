---
title: VbaProject
second_title: อ้างอิง API ของ Aspose.Slides for Java
description: เป็นตัวแทนของโปรเจกต์ VBA ที่มีมาโครการนำเสนอ.
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

เป็นตัวแทนของโครงการ VBA ที่มีมาโครการนำเสนอ.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [VbaProject()](#VbaProject--) | คอนสตรัคเตอร์นี้สร้างโครงการ VBA ใหม่จากศูนย์. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | คอนสตรัคเตอร์นี้โหลดโครงการ VBA จากการแสดงผลไบนารีของคอนเทนเนอร์ OLE. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | คืนชื่อของโครงการ VBA. |
| [getModules()](#getModules--) | คืนรายการของโมดูลทั้งหมดที่อยู่ในโครงการ VBA. |
| [getReferences()](#getReferences--) | คืนรายการของอ้างอิงทั้งหมดที่อยู่ในโครงการ VBA. |
| [toBinary()](#toBinary--) | คืนการแสดงผลไบนารีของโครงการ VBA ในรูป OLE container |
| [isPasswordProtected()](#isPasswordProtected--) | บ่งบอกว่า VBAProject ถูกป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติของโครงการหรือไม่. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

คอนสตรัคเตอร์นี้สร้างโครงการ VBA ใหม่จากศูนย์ โครงการจะถูกสร้างใน 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

คอนสตรัคเตอร์นี้โหลดโครงการ VBA จากการแสดงผลไบนารีของคอนเทนเนอร์ OLE.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

คืนชื่อของโครงการ VBA. อ่านอย่างเดียว String.

**ค่าที่คืน:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

คืนรายการของโมดูลทั้งหมดที่อยู่ในโครงการ VBA. อ่านอย่างเดียว [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**ค่าที่คืน:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

คืนรายการของอ้างอิงทั้งหมดที่อยู่ในโครงการ VBA. อ่านอย่างเดียว [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**ค่าที่คืน:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

คืนการแสดงผลไบนารีของโครงการ VBA ในรูป OLE container

**ค่าที่คืน:**
byte[] - การแสดงผลไบนารีของโครงการ VBA ในรูป OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

บ่งบอกว่า VBAProject ถูกป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติของโครงการหรือไม่. อ่านอย่างเดียว  boolean .

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


**ค่าที่คืน:**
boolean