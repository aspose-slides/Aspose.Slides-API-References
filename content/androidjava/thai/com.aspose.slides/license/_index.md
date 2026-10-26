---
title: License
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้เมธอดสำหรับการให้ลิขสิทธิ์ส่วนประกอบ
type: docs
url: /th/com.aspose.slides/license/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำมาใช้งานทั้งหมด:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

ให้เมธอดสำหรับการให้ลิขสิทธิ์ส่วนประกอบนี้.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Constructors

| ตัวสร้าง | รายละเอียด |
| --- | --- |
| [License()](#License--) | กำหนดค่าเริ่มต้นของอินสแตนซ์ใหม่ของคลาสนี้. |
## Methods

| เมธอด | รายละเอียด |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | ให้ลิขสิทธิ์กับส่วนประกอบนี้. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | ให้ลิขสิทธิ์กับส่วนประกอบนี้. |
| [getVersion()](#getVersion--) | ส่งคืนเวอร์ชันของ Aspose.Slides สำหรับ Android ผ่าน Java. |
| [resetLicense()](#resetLicense--) | รีเซ็ตลิขสิทธิ์. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


กำหนดค่าเริ่มต้นของอินสแตนซ์ใหม่ของคลาสนี้.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


ให้ลิขสิทธิ์กับส่วนประกอบนี้.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่มีลิขสิทธิ์ ใช้ค่า null เพื่อสลับเป็นโหมดประเมินผล. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


ให้ลิขสิทธิ์กับส่วนประกอบนี้.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| namePath | java.lang.String | สามารถเป็นชื่อไฟล์เต็มหรือสั้น หรือชื่อของทรัพยากรฝังอยู่ ใช้สตริงเปล่าเพื่อสลับเป็นโหมดประเมินผล. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


ส่งคืนเวอร์ชันของ Aspose.Slides สำหรับ Android ผ่าน Java.

**ส่งคืน:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


รีเซ็ตลิขสิทธิ์ ใช้วิธีนี้เพื่อรีเซ็ตลิขสิทธิ์ในส่วนประกอบ.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


ตรวจสอบว่ามีการใช้ลิขสิทธิ์กับส่วนประกอบหรือไม่

**ส่งคืน:**
boolean