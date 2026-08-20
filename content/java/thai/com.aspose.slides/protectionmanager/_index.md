---
title: ProtectionManager
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: การจัดการการป้องกันด้วยรหัสผ่านของการนำเสนอ.
type: docs
url: /th/com.aspose.slides/protectionmanager/
---
**Inheritance:**  
การสืบทอด

**All Implemented Interfaces:**  
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)  
```
public final class ProtectionManager implements IProtectionManager
```

การจัดการการป้องกันด้วยรหัสผ่านของการนำเสนอ  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | คุณสมบัตินี้มีความหมายเมื่อการนำเสนอถูกป้องกันด้วยรหัสผ่าน. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | คุณสมบัตินี้มีความหมายเมื่อการนำเสนอถูกป้องกันด้วยรหัสผ่าน. |
| [isEncrypted()](#isEncrypted--) | รับค่าที่บ่งบอกว่าตัวอย่างนี้ถูกเข้ารหัสหรือไม่. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | คุณสมบัตินี้มีความหมายเมื่อไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารในไฟล์นี้เป็นสาธารณะ. |
| [isWriteProtected()](#isWriteProtected--) | รับค่าที่บ่งบอกว่าการนำเสนอนี้ถูกป้องกันการเขียนหรือไม่. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | เข้ารหัสการนำเสนอด้วยรหัสผ่านที่ระบุ. |
| [removeEncryption()](#removeEncryption--) | ลบการเข้ารหัส. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | ตั้งค่าการป้องกันการเขียนสำหรับการนำเสนอนี้ด้วยรหัสผ่านที่ระบุ. |
| [removeWriteProtection()](#removeWriteProtection--) | ลบการป้องกันการเขียนสำหรับการนำเสนอนี้. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | กำหนดว่าการนำเสนอนี้ถูกป้องกันด้วยรหัสผ่านเพื่อการแก้ไขหรือไม่. |
| [getEncryptionPassword()](#getEncryptionPassword--) | รับรหัสผ่านที่ใช้สำหรับการเข้ารหัสการนำเสนอ. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | รับหรือกำหนดคำแนะนำการอ่านอย่างเดียว. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | รับหรือกำหนดคำแนะนำการอ่านอย่างเดียว. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

คุณสมบัตินี้มีความหมายเมื่อการนำเสนอถูกป้องกันด้วยรหัสผ่าน. หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ. หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะขณะการนำเสนอถูกเข้ารหัส. บูลีน (อ่าน/เขียน)

**Returns:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

คุณสมบัตินี้มีความหมายเมื่อการนำเสนอถูกป้องกันด้วยรหัสผ่าน. หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ. หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะขณะการนำเสนอถูกเข้ารหัส. บูลีน (อ่าน/เขียน)

**Parameters:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

รับค่าที่บ่งบอกว่าตัวอย่างนี้ถูกเข้ารหัสหรือไม่. บูลีน (อ่านอย่างเดียว)

Value: true if presentation was loaded from encrypted file or \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**Returns:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

คุณสมบัตินี้มีความหมายเมื่อไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารในไฟล์นี้เป็นสาธารณะ ค่า true หมายถึงจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์การนำเสนอที่เข้ารหัสโดยไม่ใช้รหัสผ่าน ค่า false หมายถึงจะโหลดการนำเสนอทั้งหมดที่เข้ารหัสโดยใช้รหัสผ่านที่ถูกต้อง ไม่ได้โหลดเฉพาะคุณสมบัติของเอกสาร หากการนำเสนอไม่ได้ถูกเข้ารหัสค่าคุณสมบัติก็จะเป็น false เสมอ หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่เป็นสาธารณะค่าก็จะเป็น false เสมอ หาก Presentation.EncryptDocumentProperties เป็น true ค่าของ IsOnlyDocumentPropertiesLoaded จะเป็น false เสมอ บูลีน (อ่านอย่างเดียว)

**Returns:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

รับค่าที่บ่งบอกว่าการนำเสนอนี้ถูกป้องกันการเขียนหรือไม่. บูลีน (อ่านอย่างเดียว)

**Returns:**  
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

เข้ารหัสการนำเสนอด้วยรหัสผ่านที่ระบุ.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| encryptionPassword | java.lang.String | รหัสผ่าน. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

ลบการเข้ารหัส.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

ตั้งค่าการป้องกันการเขียนสำหรับการนำเสนอนี้ด้วยรหัสผ่านที่ระบุ.

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีตั้งการป้องกันการเขียนให้กับการนำเสนอ.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่าน. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

ลบการป้องกันการเขียนสำหรับการนำเสนอนี้.

--------------------

> ```
> ตัวอย่างโค้ดนี้แสดงวิธีการลบการป้องกันการเขียนจาก PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

กำหนดว่าการนำเสนอนี้ถูกป้องกันด้วยรหัสผ่านเพื่อการแก้ไขหรือไม่.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่านสำหรับการตรวจสอบ. |

1. คุณควรตรวจสอบคุณสมบัติ (\#isWriteProtected.isWriteProtected) ก่อนเรียกใช้เมธอดนี้. 2. เมื่อรหัสผ่านเป็น null หรือว่างเปล่าเมธอดนี้จะคืนค่า false.  

**Returns:**  
boolean - True if the password is valid; otherwise, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

รับรหัสผ่านที่ใช้สำหรับการเข้ารหัสการนำเสนอ. สตริง (อ่านอย่างเดียว).

**Returns:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

รับหรือกำหนดคำแนะนำการอ่านอย่างเดียว. บูลีน (อ่าน/เขียน)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**  
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

รับหรือกำหนดคำแนะนำการอ่านอย่างเดียว. บูลีน (อ่าน/เขียน)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |