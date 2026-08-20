---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: ข้อมูลเกี่ยวกับไฟล์งานนำเสนอ
type: docs
url: /th/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

ข้อมูลเกี่ยวกับไฟล์งานนำเสนอ
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | คืนค่า True หากงานนำเสนอที่เชื่อมต่อถูกเข้ารหัส, มิฉะนั้น False. |
| [isPasswordProtected()](#isPasswordProtected--) | รับค่าที่บ่งชี้ว่างานนำเสนอที่เชื่อมต่อถูกป้องกันด้วยรหัสผ่านเพื่อเปิด. |
| [isWriteProtected()](#isWriteProtected--) | รับค่าที่บ่งชี้ว่างานนำเสนอที่เชื่อมต่อถูกป้องกันการเขียน. |
| [getLoadFormat()](#getLoadFormat--) | รับรูปแบบของงานนำเสนอที่เชื่อมต่อ. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับงานนำเสนอที่ถูกป้องกันด้วยรหัสเปิดหรือไม่. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | ตรวจสอบว่ารหัสผ่านเพื่อแก้ไขถูกต้องสำหรับงานนำเสนอที่ป้องกันการเขียนหรือไม่. |
| [readDocumentProperties()](#readDocumentProperties--) | รับคุณสมบัติเอกสารของงานนำเสนอที่เชื่อมต่อ. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | อัปเดตคุณสมบัติของงานนำเสนอที่เชื่อมต่อ. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | เขียนงานนำเสนอที่เชื่อมต่อไปยังสตรีม. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | เขียนงานนำเสนอที่เชื่อมต่อไปยังไฟล์. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

รับค่า True หากงานนำเสนอที่เชื่อมต่อถูกเข้ารหัส, มิฉะนั้น False. บูลีน (อ่านอย่างเดียว)

**คืนค่า:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

รับค่าที่บ่งชี้ว่างานนำเสนอที่เชื่อมต่อถูกป้องกันด้วยรหัสผ่านเพื่อเปิด.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**คืนค่า:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

รับค่าที่บ่งชี้ว่างานนำเสนอที่เชื่อมต่อถูกป้องกันการเขียน.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


---

หากงานนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อเปิด, ค่า property จะเท่ากับ NotDefined. ดู enumeration [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

รับรูปแบบของงานนำเสนอที่เชื่อมต่อ. [LoadFormat](../../com.aspose.slides/loadformat) (อ่านอย่างเดียว).

**คืนค่า:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับงานนำเสนอที่ถูกป้องกันด้วยรหัสเปิดหรือไม่.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่านที่จะตรวจสอบ. |

เมื่อรหัสผ่านเป็น null หรือว่าง, เมธอดนี้จะคืนค่า false. |

**คืนค่า:**
boolean - True หากงานนำเสนอถูกป้องกันด้วยรหัสเปิดและรหัสผ่านถูกต้องและ false มิฉะนั้น

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

ตรวจสอบว่ารหัสผ่านเพื่อแก้ไขถูกต้องสำหรับงานนำเสนอที่ป้องกันการเขียนหรือไม่.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่านที่จะตรวจสอบ. |

1. คุณควรตรวจสอบ property (\#isWriteProtected.isWriteProtected) ก่อนเรียกเมธอดนี้. 2. เมื่อรหัสผ่านเป็น null หรือว่าง, เมธอดนี้จะคืนค่า false. |

**คืนค่า:**
boolean - True หากงานนำเสนอถูกป้องกันการเขียนและรหัสผ่านถูกต้อง. False มิฉะนั้น

### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

รับคุณสมบัติเอกสารของงานนำเสนอที่เชื่อมต่อ.

**คืนค่า:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - คุณสมบัติเอกสาร [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

อัปเดตคุณสมบัติของงานนำเสนอที่เชื่อมต่อ.

---

> ```
> ตัวอย่างนี้แสดงวิธีการเรียกเมธอด #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) เพื่อ
>  อัปเดตคุณสมบัติเอกสารที่ได้จากการเรียกเมธอด #readDocumentProperties.readDocumentProperties
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | คุณสมบัติเอกสาร [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

เขียนงานนำเสนอที่เชื่อมต่อไปยังสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมต้องสามารถเลื่อนตำแหน่งและเขียนได้. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

เขียนงานนำเสนอที่เชื่อมต่อไปยังไฟล์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์งานนำเสนอ. |