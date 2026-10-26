---
title: DigitalSignature
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ลายเซ็นดิจิทัลในไฟล์ที่เซ็น
type: docs
url: /th/com.aspose.slides/digitalsignature/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำไว้ทั้งหมด:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

ลายเซ็นดิจิทัลในไฟล์ที่เซ็น.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // เริ่มต้นอินสแตนซ์ Presentation
>  Presentation pres = new Presentation();
>  try {
>     // สร้างอ็อบเจ็กต์ DigitalSignature ด้วยไฟล์ PFX และรหัสผ่าน PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // คอมเมนต์ลายเซ็นดิจิทัลใหม่
>      signature.setComments("Aspose.Slides digital signing test.");
>      // เพิ่มลายเซ็นดิจิทัลเข้าไปในพรีเซนเทชัน
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
>          // ตรวจสอบว่าลายเซ็นดิจิทัลทั้งหมดเป็นค่าที่ถูกต้องหรือไม่
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

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | สร้างอ็อบเจ็กต์ DigitalSignature ใหม่ด้วยใบรับรองที่ระบุ |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | สร้างอ็อบเจ็กต์ DigitalSignature ใหม่ด้วยเส้นทางไฟล์ใบรับรองและรหัสผ่านที่ระบุ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCertificate()](#getCertificate--) | อ็อบเจ็กต์ Certificate ที่ใช้เพื่อเซ็นเอกสาร |
| [isValid()](#isValid--) | หากลายเซ็นดิจิทัลนี้เป็นค่าที่ถูกต้องและเอกสารไม่ได้ถูกดัดแปลง ค่านี้จะเป็น true |
| [getSignTime()](#getSignTime--) | เวลาที่เอกสารถูกเซ็น |
| [getComments()](#getComments--) | วัตถุประสงค์ของลายเซ็น |
| [setComments(String value)](#setComments-java.lang.String-) | วัตถุประสงค์ของลายเซ็น |

### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

สร้างอ็อบเจ็กต์ DigitalSignature ใหม่ด้วยใบรับรองที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| certData | byte[] | อาร์เรย์ไบต์ที่บรรจุใบรับรอง |
| password | java.lang.String | รหัสผ่านที่จำเป็นเพื่อเข้าถึงใบรับรอง |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

สร้างอ็อบเจ็กต์ DigitalSignature ใหม่ด้วยเส้นทางไฟล์ใบรับรองและรหัสผ่านที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filePath | java.lang.String | เส้นทางไปยังไฟล์ที่มีใบรับรอง |
| password | java.lang.String | รหัสผ่านที่จำเป็นเพื่อเข้าถึงใบรับรอง |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

อ็อบเจ็กต์ Certificate ที่ใช้เพื่อเซ็นเอกสาร. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]

### isValid() {#isValid--}
```
public final boolean isValid()
```

หากลายเซ็นดิจิทัลนี้เป็นค่าที่ถูกต้องและเอกสารไม่ได้ถูกดัดแปลง ค่านี้จะเป็น true. อ่านอย่างเดียว boolean.

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

**คืนค่า:**
boolean

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

เวลาที่เอกสารถูกเซ็น. อ่านอย่างเดียว java.util.Date.

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


**คืนค่า:**
java.util.Date

### getComments() {#getComments--}
```
public final String getComments()
```

วัตถุประสงค์ของลายเซ็น. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

วัตถุประสงค์ของลายเซ็น. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |