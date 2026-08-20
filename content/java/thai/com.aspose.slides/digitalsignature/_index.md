---
title: DigitalSignature
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม.
type: docs
url: /th/com.aspose.slides/digitalsignature/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // เริ่มต้นอินสแตนซ์ Presentation
>  Presentation pres = new Presentation();
>  try {
>     // สร้างออบเจกต์ DigitalSignature ด้วยไฟล์ PFX และรหัสผ่าน PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // แสดงความคิดเห็นลายเซ็นดิจิทัลใหม่
>      signature.setComments("Aspose.Slides digital signing test.");
>      // เพิ่มลายเซ็นดิจิทัลลงในพรีเซนเทชัน
>      pres.getDigitalSignatures().add(signature);
>      // บันทึกพรีเซนเทชัน
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // เริ่มต้นอินสแตนซ์ Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // ตรวจสอบว่าลายเซ็นดิจิทัลทั้งหมดเป็นแบบถูกต้องหรือไม่
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | สร้างวัตถุ DigitalSignature ใหม่ด้วยใบรับรองที่ระบุ |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | สร้างวัตถุ DigitalSignature ใหม่ด้วยเส้นทางไฟล์ใบรับรองและรหัสผ่านที่ระบุ |
## เมธอด

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | อ็อบเจ็กต์ใบรับรองที่ใช้ลงนามเอกสาร |
| [isValid()](#isValid--) | หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่ได้ถูกดัดแปลง ค่าจะเป็น true |
| [getSignTime()](#getSignTime--) | เวลาที่เอกสารถูกลงนาม |
| [getComments()](#getComments--) | จุดประสงค์ของลายเซ็น |
| [setComments(String value)](#setComments-java.lang.String-) | จุดประสงค์ของลายเซ็น |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


สร้างวัตถุ DigitalSignature ใหม่ด้วยใบรับรองที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| certData | byte[] | อาเรย์ไบต์ที่บรรจุใบรับรอง |
| password | java.lang.String | รหัสผ่านที่ต้องการเพื่อเข้าถึงใบรับรอง |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


สร้างวัตถุ DigitalSignature ใหม่ด้วยเส้นทางไฟล์ใบรับรองและรหัสผ่านที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | เส้นทางไปยังไฟล์ที่มีใบรับรอง |
| password | java.lang.String | รหัสผ่านที่ต้องการเพื่อเข้าถึงใบรับรอง |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


อ็อบเจ็กต์ใบรับรองที่ใช้ลงนามเอกสาร อ่านอย่างเดียว byte[].

**ผลลัพธ์:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่ได้ถูกดัดแปลง ค่าจะเป็น true อ่านอย่างเดียว boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


เวลาที่เอกสารถูกลงนาม อ่านอย่างเดียว java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


จุดประสงค์ของลายเซ็น อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


จุดประสงค์ของลายเซ็น อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |