---
title: IVbaProject
second_title: Aspose.Slides for Android via Java API Reference
description: แทนโครงการ VBA ที่มีมาโครการนำเสนอ.
type: docs
url: /th/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

แทนโครงการ VBA ที่มีมาโครการนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | ส่งคืนชื่อของโครงการ VBA. |
| [getModules()](#getModules--) | ส่งคืนรายการของโมดูลทั้งหมดที่อยู่ในโครงการ VBA. |
| [getReferences()](#getReferences--) | ส่งคืนรายการของการอ้างอิงทั้งหมดที่อยู่ในโครงการ VBA. |
| [toBinary()](#toBinary--) | ส่งคืนการแทนค่ารูปแบบไบนารีของโครงการ VBA ในรูปแบบคอนเทนเนอร์ OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | ระบุว่า VBAProject ถูกป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติโครงการหรือไม่. |
### getName() {#getName--}
```
public abstract String getName()
```


ส่งคืนชื่อของโครงการ VBA. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


ส่งคืนรายการของโมดูลทั้งหมดที่อยู่ในโครงการ VBA. อ่านอย่างเดียว [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**คืนค่า:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


ส่งคืนรายการของการอ้างอิงทั้งหมดที่อยู่ในโครงการ VBA. อ่านอย่างเดียว [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**คืนค่า:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


ส่งคืนการแทนค่ารูปแบบไบนารีของโครงการ VBA ในรูปแบบคอนเทนเนอร์ OLE. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[] - การแทนค่ารูปแบบไบนารีของโครงการ VBA ในรูปแบบคอนเทนเนอร์ OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


ระบุว่า VBAProject ถูกป้องกันด้วยรหัสผ่านเพื่อดูคุณสมบัติโครงการหรือไม่. อ่านอย่างเดียว boolean.

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