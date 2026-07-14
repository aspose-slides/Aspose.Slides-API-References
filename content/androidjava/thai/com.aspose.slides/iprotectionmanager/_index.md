---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation password protection management.
type: docs
url: /th/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

การจัดการการป้องกันด้วยรหัสผ่านของการนำเสนอ.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | คุณสมบัตินี้มีความหมาย หากการนำเสนอถูกป้องกันด้วยรหัสผ่าน. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | คุณสมบัตินี้มีความหมาย หากการนำเสนอถูกป้องกันด้วยรหัสผ่าน. |
| [isEncrypted()](#isEncrypted--) | รับค่าที่บ่งชี้ว่าตัวอย่างนี้ถูกเข้ารหัสหรือไม่. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | คุณสมบัตินี้มีความหมาย หากไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารในไฟล์นี้เป็นสาธารณะ. |
| [isWriteProtected()](#isWriteProtected--) | รับค่าที่บ่งชี้ว่าการนำเสนอฉบับนี้ถูกป้องกันการเขียนหรือไม่. |
| [getEncryptionPassword()](#getEncryptionPassword--) | คืนค่ารหัสผ่านการเข้ารหัส. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | รับหรือกำหนดคำแนะนำให้เป็นอ่านอย่างเดียว. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | รับหรือกำหนดคำแนะนำให้เป็นอ่านอย่างเดียว. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | เข้ารหัสการนำเสนอด้วยรหัสผ่านที่ระบุ. |
| [removeEncryption()](#removeEncryption--) | ลบการเข้ารหัส. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | ตั้งค่าการป้องกันการเขียนสำหรับการนำเสนอฉบับนี้ด้วยรหัสผ่านที่ระบุ. |
| [removeWriteProtection()](#removeWriteProtection--) | ลบการป้องกันการเขียนสำหรับการนำเสนอฉบับนี้. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | กำหนดว่าการนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อการแก้ไขหรือไม่. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

คุณสมบัตินี้มีความหมาย หากการนำเสนอถูกป้องกันด้วยรหัสผ่าน หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะในขณะที่การนำเสนอถูกเข้ารหัส บูลีนอ่าน/เขียน.

**คืนค่า:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

คุณสมบัตินี้มีความหมาย หากการนำเสนอถูกป้องกันด้วยรหัสผ่าน หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะในขณะที่การนำเสนอถูกเข้ารหัส บูลีนอ่าน/เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

รับค่าที่บ่งชี้ว่าตัวอย่างนี้ถูกเข้ารหัสหรือไม่ บูลีนอ่านอย่างเดียว.

**ค่า:**
true หากการนำเสนอถูกโหลดจากไฟล์ที่เข้ารหัสหรือเมธอด \#encrypt(String).encrypt(String) ถูกเรียกใช้; ไม่เช่นนั้น false.

**คืนค่า:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

คุณสมบัตินี้มีความหมาย หากไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารในไฟล์นี้เป็นสาธารณะ ค่า true หมายความว่ามีการโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์การนำเสนอที่เข้ารหัสโดยไม่ใช้รหัสผ่าน ค่า false หมายความว่ามีการโหลดการนำเสนอที่เข้ารหัสทั้งหมดด้วยรหัสผ่านที่ถูกต้อง ไม่ได้โหลดเฉพาะคุณสมบัติของเอกสาร หากการนำเสนอไม่ได้ถูกเข้ารหัส คุณสมบัตินี้จะมีค่าเป็น false เสมอ หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่เป็นสาธารณะ คุณสมบัตินี้จะมีค่าเป็น false เสมอ หาก PresentationEx.EncryptDocumentProperties เป็น true ค่าของ IsOnlyDocumentPropertiesLoaded จะเป็น false เสมอ บูลีนอ่านอย่างเดียว.

**คืนค่า:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

รับค่าที่บ่งชี้ว่าการนำเสนอฉบับนี้ถูกป้องกันการเขียนหรือไม่ บูลีนอ่านอย่างเดียว.

**คืนค่า:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

คืนค่ารหัสผ่านการเข้ารหัส. สตริงอ่านอย่างเดียว.

**คืนค่า:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

รับหรือกำหนดคำแนะนำให้เป็นอ่านอย่างเดียว. บูลีนอ่าน/เขียน.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**คืนค่า:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

รับหรือกำหนดคำแนะนำให้เป็นอ่านอย่างเดียว. บูลีนอ่าน/เขียน.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

เข้ารหัสการนำเสนอด้วยรหัสผ่านที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| encryptionPassword | java.lang.String | รหัสผ่าน. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

ลบการเข้ารหัส.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

ตั้งค่าการป้องกันการเขียนสำหรับการนำเสนอฉบับนี้ด้วยรหัสผ่านที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่าน. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

ลบการป้องกันการเขียนสำหรับการนำเสนอฉบับนี้.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

กำหนดว่าการนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อการแก้ไขหรือไม่.

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
| password | java.lang.String | รหัสผ่านสำหรับการตรวจสอบ. |

1. คุณควรตรวจสอบคุณสมบัติ (\#isWriteProtected.isWriteProtected) ก่อนเรียกเมธอดนี้. 2. เมื่อรหัสผ่านเป็น null หรือว่างเปล่า เมธอดนี้จะคืนค่า false. |

**คืนค่า:**
boolean - true หากรหัสผ่านถูกต้อง; ไม่เช่นนั้น false.