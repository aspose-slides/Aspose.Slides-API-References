---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม
type: docs
url: /th/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCertificate()](#getCertificate--) | อ็อบเจกต์ Certificate ที่ใช้ในการลงนามเอกสาร. อ่านอย่างเดียว byte[]. |
| [isValid()](#isValid--) | หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่มีการดัดแปลง ค่าที่นี้จะเป็นจริง. อ่านอย่างเดียว boolean. |
| [getSignTime()](#getSignTime--) | เวลาเมื่อเอกสารถูกลงนาม. อ่านอย่างเดียว java.util.Date. |
| [getComments()](#getComments--) | วัตถุประสงค์ของลายเซ็น. อ่าน/เขียน String. |
| [setComments(String value)](#setComments-java.lang.String-) | วัตถุประสงค์ของลายเซ็น. อ่าน/เขียน String. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

อ็อบเจกต์ Certificate ที่ใช้ในการลงนามเอกสาร. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่มีการดัดแปลง ค่าที่นี้จะเป็นจริง. อ่านอย่างเดียว boolean.

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

**คืนค่า:**
boolean
### getSignTime() {#getSignTime--}
```
public abstract Date getSignTime()
```

เวลาเมื่อเอกสารถูกลงนาม. อ่านอย่างเดียว java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

วัตถุประสงค์ของลายเซ็น. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

วัตถุประสงค์ของลายเซ็น. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |