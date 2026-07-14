---
title: PresentationInfo
second_title: Aspose.Slides for Android ผ่าน Java API Reference
description: ข้อมูลเกี่ยวกับไฟล์การนำเสนอ
type: docs
url: /th/com.aspose.slides/presentationinfo/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)  
```
public final class PresentationInfo implements IPresentationInfo
```

ข้อมูลเกี่ยวกับไฟล์การนำเสนอ
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | รับค่า True หากการนำเสนอที่ผูกไว้ถูกเข้ารหัส, มิฉะนั้น False. อ่านอย่างเดียว boolean. |
| [isPasswordProtected()](#isPasswordProtected--) | รับค่าที่บ่งบอกว่าการนำเสนอที่ผูกไว้ถูกป้องกันด้วยรหัสผ่านเพื่อเปิดหรือไม่. |
| [isWriteProtected()](#isWriteProtected--) | รับค่าที่บ่งบอกว่าการนำเสนอที่ผูกไว้ถูกป้องกันการเขียนหรือไม่. |
| [getLoadFormat()](#getLoadFormat--) | รับรูปแบบของการนำเสนอที่ผูกไว้. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับการนำเสนอที่ป้องกันด้วยรหัสผ่านเปิดหรือไม่. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | ตรวจสอบว่ารหัสผ่านเพื่อแก้ไขถูกต้องสำหรับการนำเสนอที่ป้องกันการเขียนหรือไม่. |
| [readDocumentProperties()](#readDocumentProperties--) | รับคุณสมบัติเ�เอกสารของการนำเสนอที่ผูกไว้. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | อัปเดตคุณสมบัติของการนำเสนอที่ผูกไว้. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | เขียนการนำเสนอที่ผูกไว้ไปยังสตรีม. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | เขียนการนำเสนอที่ผูกไว้ไปยังไฟล์. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

รับค่า True หากการนำเสนอที่ผูกไว้ถูกเข้ารหัส, มิฉะนั้น False. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

รับค่าที่บ่งบอกว่าการนำเสนอที่ผูกไว้ถูกป้องกันด้วยรหัสผ่านเพื่อเปิดหรือไม่.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**คืนค่า:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

รับค่าที่บ่งบอกว่าการนำเสนอที่ผูกไว้ถูกป้องกันการเขียนหรือไม่.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

หากการนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อเปิด, ค่า property จะเท่ากับ NotDefined.

**คืนค่า:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

รับรูปแบบของการนำเสนอที่ผูกไว้. อ่านอย่างเดียว [LoadFormat](../../com.aspose.slides/loadformat).

**คืนค่า:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับการนำเสนอที่ป้องกันด้วยรหัสผ่านเปิดหรือไม่.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่านที่จะตรวจสอบ. |

--------------------

เมื่อรหัสผ่านเป็น null หรือว่างเปล่า, เมธอดนี้จะคืนค่า false. |

**คืนค่า:**
boolean - True หากการนำเสนอถูกป้องกันด้วยรหัสผ่านเปิดและรหัสผ่านถูกต้อง; false ในกรณีอื่น.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

ตรวจสอบว่ารหัสผ่านเพื่อแก้ไขถูกต้องสำหรับการนำเสนอที่ป้องกันการเขียนหรือไม่.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่านที่จะตรวจสอบ. |

--------------------

1. คุณควรตรวจสอบ property (\#isWriteProtected.isWriteProtected) ก่อนเรียกเมธอดนี้. 2. เมื่อรหัสผ่านเป็น null หรือว่างเปล่า, เมธอดนี้จะคืนค่า false. |

**คืนค่า:**
boolean - True หากการนำเสนอถูกป้องกันการเขียนและรหัสผ่านถูกต้อง. False ในกรณีอื่น.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

รับคุณสมบัติเ�เอกสารของการนำเสนอที่ผูกไว้.

**คืนค่า:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

อัปเดตคุณสมบัติของการนำเสนอที่ผูกไว้.

--------------------

> ```
> ตัวอย่างนี้แสดงวิธีการเรียกเมธอด #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) เพื่อ
>  อัปเดตคุณสมบัติเอกสารที่ได้รับจากการเรียกเมธอด #readDocumentProperties.readDocumentProperties
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

เขียนการนำเสนอที่ผูกไว้ไปยังสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมต้องสามารถเลื่อนได้และเขียนได้. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

เขียนการนำเสนอที่ผูกไว้ไปยังไฟล์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์การนำเสนอ. |