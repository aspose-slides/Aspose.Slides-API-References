---
title: IDigitalSignature
second_title: Aspose.Slides for Java API Reference
description: ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม.
type: docs
url: /th/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCertificate()](#getCertificate--) | อ็อบเจ็กต์ใบรับรองที่ใช้ลงนามในเอกสาร |
| [isValid()](#isValid--) | หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่ได้ถูกแก้ไข ค่าจะเป็น true |
| [getSignTime()](#getSignTime--) | เวลาที่เอกสารถูกลงนาม |
| [getComments()](#getComments--) | จุดประสงค์ของลายเซ็น |
| [setComments(String value)](#setComments-java.lang.String-) | จุดประสงค์ของลายเซ็น |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```


อ็อบเจ็กต์ใบรับรองที่ใช้ลงนามในเอกสาร. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```


หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่ได้ถูกแก้ไข ค่าจะเป็น true. อ่านอย่างเดียว boolean.

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


เวลาที่เอกสารถูกลงนาม. อ่านอย่างเดียว java.util.Date.

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


จุดประสงค์ของลายเซ็น. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


จุดประสงค์ของลายเซ็น. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |