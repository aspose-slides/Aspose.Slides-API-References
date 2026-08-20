---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: แสดงถึงโครงการ VBA ที่มีมาโครการนำเสนอ.
type: docs
url: /th/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

แสดงถึงโครงการ VBA ที่มีมาโครการนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | ส่งคืนชื่อของโครงการ VBA. |
| [getModules()](#getModules--) | ส่งคืนรายการของโมดูลทั้งหมดที่อยู่ในโครงการ VBA. |
| [getReferences()](#getReferences--) | ส่งคืนรายการของการอ้างอิงทั้งหมดที่อยู่ในโครงการ VBA. |
| [toBinary()](#toBinary--) | ส่งคืนการแทนค่าไบต์ของโครงการ VBA ในรูปแบบ OLE container. |
| [isPasswordProtected()](#isPasswordProtected--) | บ่งชี้ว่า VBAProject ได้รับการป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติของโครงการหรือไม่. |
### getName() {#getName--}
```
public abstract String getName()
```

ส่งคืนชื่อของโครงการ VBA. String แบบอ่านอย่างเดียว.

**ส่งคืน:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

ส่งคืนรายการของโมดูลทั้งหมดที่อยู่ในโครงการ VBA. อ่านอย่างเดียว [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**ส่งคืน:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

ส่งคืนรายการของการอ้างอิงทั้งหมดที่อยู่ในโครงการ VBA. อ่านอย่างเดียว [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**ส่งคืน:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

ส่งคืนการแทนค่าไบต์ของโครงการ VBA ในรูปแบบ OLE container. อ่านอย่างเดียว byte[].

**ส่งคืน:**
byte[] - การแสดงผลแบบไบนารีของโครงการ VBA ในรูปแบบ OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

บ่งชี้ว่า VBAProject ได้รับการป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติของโครงการหรือไม่. boolean แบบอ่านอย่างเดียว.

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


**ส่งคืน:**
boolean