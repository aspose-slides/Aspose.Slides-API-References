---
title: IPresentationInfo
second_title: Aspose.Slidesสำหรับ Androidผ่าน Java API Reference
description: ข้อมูลเกี่ยวกับไฟล์พรีเซนเทชั่น
type: docs
url: /th/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

ข้อมูลเกี่ยวกับไฟล์พรีเซนเทชั่น
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | รับค่า True หากพรีเซนเทชั่นที่เชื่อมต่อถูกเข้ารหัส, มิฉะนั้นเป็น False. |
| [isPasswordProtected()](#isPasswordProtected--) | รับค่าที่บ่งชี้ว่าพรีเซนเทชั่นที่เชื่อมต่อถูกป้องกันด้วยรหัสผ่านเพื่อเปิดหรือไม่. |
| [isWriteProtected()](#isWriteProtected--) | รับค่าที่บ่งชี้ว่าพรีเซนเทชั่นที่เชื่อมต่อถูกป้องกันการเขียนหรือไม่. |
| [getLoadFormat()](#getLoadFormat--) | รับรูปแบบของพรีเซนเทชั่นที่เชื่อมต่อ. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | ตรวจสอบว่ารหัสผ่านสำหรับพรีเซนเทชั่นที่มีรหัสผ่านเปิดถูกต้องหรือไม่. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | ตรวจสอบว่ารหัสผ่านสำหรับแก้ไขสำหรับพรีเซนเทชั่นที่ป้องกันการเขียนถูกต้องหรือไม่. |
| [readDocumentProperties()](#readDocumentProperties--) | รับคุณสมบัติของเอกสารของพรีเซนเทชั่นที่เชื่อมต่อ. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | อัปเดตคุณสมบัติของพรีเซนเทชั่นที่เชื่อมต่อ. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | เขียนพรีเซนเทชั่นที่เชื่อมต่อไปยังสตรีม. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | เขียนพรีเซนเทชั่นที่เชื่อมต่อไปยังไฟล์. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

รับค่า True หากพรีเซนเทชั่นที่เชื่อมต่อถูกเข้ารหัส, มิฉะนั้นเป็น False. อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

รับค่าที่บ่งชี้ว่าพรีเซนเทชั่นที่เชื่อมต่อถูกป้องกันด้วยรหัสผ่านเพื่อเปิดหรือไม่.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**ผลลัพธ์:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

รับค่าที่บ่งชี้ว่าพรีเซนเทชั่นที่เชื่อมต่อถูกป้องกันการเขียนหรือไม่.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

หากพรีเซนเทชั่นถูกป้องกันด้วยรหัสผ่านเพื่อเปิด, ค่าของคุณสมบัติจะเท่ากับ NotDefined. ดู enumeration [NullableBool](../../com.aspose.slides/nullablebool).

**ผลลัพธ์:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

รับรูปแบบของพรีเซนเทชั่นที่เชื่อมต่อ. อ่านอย่างเดียว [LoadFormat](../../com.aspose.slides/loadformat).

**ผลลัพธ์:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

ตรวจสอบว่ารหัสผ่านสำหรับพรีเซนเทชั่นที่มีรหัสผ่านเปิดถูกต้องหรือไม่.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่านที่ต้องตรวจสอบ. |

--------------------

เมื่อรหัสผ่านเป็น null หรือว่าง, เมธอดนี้จะคืนค่า false.

**ผลลัพธ์:**
boolean - True หากพรีเซนเทชั่นถูกป้องกันด้วยรหัสผ่านเปิดและรหัสผ่านถูกต้องและ false ในกรณีอื่น.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

ตรวจสอบว่ารหัสผ่านสำหรับการแก้ไขสำหรับพรีเซนเทชั่นที่ป้องกันการเขียนถูกต้องหรือไม่.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| password | java.lang.String | รหัสผ่านที่ต้องตรวจสอบ. |

--------------------

1. คุณควรตรวจสอบคุณสมบัติ (\#isWriteProtected.isWriteProtected) ก่อนเรียกเมธอดนี้. 2. เมื่อรหัสผ่านเป็น null หรือว่าง, เมธอดนี้จะคืนค่า false.

**ผลลัพธ์:**
boolean - True หากพรีเซนเทชั่นถูกป้องกันการเขียนและรหัสผ่านถูกต้อง. False ในกรณีอื่น.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

รับคุณสมบัติของเอกสารของพรีเซนเทชั่นที่เชื่อมต่อ.

**ผลลัพธ์:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - คุณสมบัติของเอกสาร [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

อัปเดตคุณสมบัติของพรีเซนเทชั่นที่เชื่อมต่อ.

--------------------

> ```
> ตัวอย่างนี้แสดงวิธีเรียกเมธอด #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) เพื่อ
>  อัปเดตคุณสมบัติของเอกสารที่ได้รับจากการเรียกเมธอด #readDocumentProperties.readDocumentProperties

>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | คุณสมบัติของเอกสาร [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

เขียนพรีเซนเทชั่นที่เชื่อมต่อไปยังสตรีม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมต้องสามารถเลื่อน (seek) และเขียนได้. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

เขียนพรีเซนเทชั่นที่เชื่อมต่อไปยังไฟล์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| file | java.lang.String | ไฟล์พรีเซนเทชั่น. |