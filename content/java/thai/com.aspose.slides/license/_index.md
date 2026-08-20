---
title: License
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้เมธอดสำหรับการลงทะเบียนลิขสิทธิ์ของคอมโพเนนต์.
type: docs
url: /th/com.aspose.slides/license/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

ให้เมธอดสำหรับการลงทะเบียนลิขสิทธิ์ของคอมโพเนนต์.

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

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [License()](#License--) | สร้างอินสแตนซ์ใหม่ของคลาสนี้. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | ลงทะเบียนลิขสิทธิ์ให้กับคอมโพเนนต์. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | ลงทะเบียนลิขสิทธิ์ให้กับคอมโพเนนต์. |
| [getVersion()](#getVersion--) | คืนค่าเวอร์ชันของ Aspose.Slides สำหรับ Java. |
| [resetLicense()](#resetLicense--) | รีเซ็ตลิขสิทธิ์. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

สร้างอินสแตนซ์ใหม่ของคลาสนี้.

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

ลงทะเบียนลิขสิทธิ์ให้กับคอมโพเนนต์.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่มีลิขสิทธิ์ ใช้ค่า null เพื่อสลับเป็นโหมดประเมินผล. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

ลงทะเบียนลิขสิทธิ์ให้กับคอมโพเนนต์.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| namePath | java.lang.String | สามารถเป็นชื่อไฟล์เต็มหรือสั้น หรือชื่อของทรัพยากรที่ฝังอยู่ ใช้สตริงว่างเพื่อสลับเป็นโหมดประเมินผล. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

คืนค่าเวอร์ชันของ Aspose.Slides สำหรับ Java.

**คืนค่า:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

รีเซ็ตลิขสิทธิ์ ใช้วิธีนี้เพื่อรีเซ็ตลิขสิทธิ์ในคอมโพเนนต์.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

ตรวจสอบว่าลิขสิทธิ์ถูกใช้กับคอมโพเนนต์หรือไม่

**คืนค่า:**
boolean