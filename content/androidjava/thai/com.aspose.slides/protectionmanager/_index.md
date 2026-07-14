---
title: ProtectionManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: การจัดการการป้องกันรหัสผ่านของงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

การจัดการการป้องกันรหัสผ่านของงานนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | คุณสมบัตินี้มีความหมาย หากงานนำเสนอมีการป้องกันด้วยรหัสผ่าน |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | คุณสมบัตินี้มีความหมาย หากงานนำเสนอมีการป้องกันด้วยรหัสผ่าน |
| [isEncrypted()](#isEncrypted--) | รับค่าที่บ่งบอกว่าอินสแตนซ์นี้ถูกเข้ารหัสหรือไม่ |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารในไฟล์นี้เป็นสาธารณะ |
| [isWriteProtected()](#isWriteProtected--) | รับค่าที่บ่งบอกว่างานนำเสนอนี้ถูกป้องกันการเขียนหรือไม่ |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | เข้ารหัสงานนำเสนอด้วยรหัสผ่านที่ระบุ |
| [removeEncryption()](#removeEncryption--) | ลบการเข้ารหัส |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | ตั้งค่าการป้องกันการเขียนสำหรับงานนำเสนอนี้ด้วยรหัสผ่านที่ระบุ |
| [removeWriteProtection()](#removeWriteProtection--) | ลบการป้องกันการเขียนสำหรับงานนำเสนอนี้ |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | กำหนดว่างานนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อแก้ไขหรือไม่ |
| [getEncryptionPassword()](#getEncryptionPassword--) | รับรหัสผ่านที่ใช้สำหรับการเข้ารหัสงานนำเสนอ |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | รับหรือกำหนดคำแนะนำให้อ่านอย่างเดียว |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | รับหรือกำหนดคำแนะนำให้อ่านอย่างเดียว |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

คุณสมบัตินี้มีความหมาย หากงานนำเสนอถูกป้องกันด้วยรหัสผ่าน หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์งานนำเสนอ หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะในขณะที่งานนำเสนอถูกเข้ารหัส อ่าน/เขียน boolean

**คืนค่า:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

คุณสมบัตินี้มีความหมาย หากงานนำเสนอถูกป้องกันด้วยรหัสผ่าน หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์งานนำเสนอ หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะในขณะที่งานนำเสนอถูกเข้ารหัส อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

รับค่าที่บ่งบอกว่าอินสแตนซ์นี้ถูกเข้ารหัสหรือไม่ Read-only boolean

Value: true ถ้างานนำเสนอโหลดจากไฟล์ที่เข้ารหัสหรือเมธอด \#encrypt(String).encrypt(String) ถูกเรียกใช้ ; มิฉะนั้น false

**คืนค่า:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารในไฟล์นี้เป็นสาธารณะ ค่า true หมายความว่ามีการโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสโดยไม่ต้องใช้รหัสผ่าน ค่า false หมายความว่ามีการโหลดงานนำเสนอที่เข้ารหัสทั้งหมดด้วยรหัสผ่านที่ถูกต้อง ไม่ได้โหลดเฉพาะคุณสมบัติของเอกสาร หากงานนำเสนอไม่ได้ถูกเข้ารหัส คุณสมบัตินี้จะเป็น false เสมอ หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่ได้เป็นสาธารณะ คุณสมบัตินี้จะเป็น false เสมอ หาก Presentation.EncryptDocumentProperties เป็น true ค่าของ IsOnlyDocumentPropertiesLoaded จะเป็น false เสมอ Read-only boolean

**คืนค่า:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

รับค่าที่บ่งบอกว่างานนำเสนอนี้ถูกป้องกันการเขียนหรือไม่ Read-only boolean

**คืนค่า:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

เข้ารหัสงานนำเสนอด้วยรหัสผ่านที่ระบุ

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| encryptionPassword | java.lang.String | รหัสผ่าน |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

ลบการเข้ารหัส
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

ตั้งค่าการป้องกันการเขียนสำหรับงานนำเสนอนี้ด้วยรหัสผ่านที่ระบุ

--------------------

> ```
> ตัวอย่างโค้ดต่อไปนี้แสดงวิธีตั้งการป้องกันการเขียนให้กับงานนำเสนอ
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่าน |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

ลบการป้องกันการเขียนสำหรับงานนำเสนอนี้

--------------------

> ```
> ตัวอย่างโค้ดนี้แสดงวิธีการลบการป้องกันการเขียนออกจากงานนำเสนอ PowerPoint.
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

กำหนดว่างานนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อแก้ไขหรือไม่

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่านสำหรับการตรวจสอบ |

1. ควรตรวจสอบคุณสมบัติ (\#isWriteProtected.isWriteProtected) ก่อนเรียกเมธอดนี้  
2. เมื่อรหัสผ่านเป็น null หรือว่างเปล่า เมธอดนี้จะคืนค่า false

**คืนค่า:**
boolean - true หากรหัสผ่านถูกต้อง; มิฉะนั้น false
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

รับรหัสผ่านที่ใช้สำหรับการเข้ารหัสงานนำเสนอ Read-only String

**คืนค่า:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

รับหรือกำหนดคำแนะนำให้อ่านอย่างเดียว Read/write boolean

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

**คืนค่า:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

รับหรือกำหนดคำแนะนำให้อ่านอย่างเดียว Read/write boolean

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |