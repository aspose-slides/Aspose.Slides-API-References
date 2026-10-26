---
title: BlobManagementOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวเลือกที่สามารถใช้จัดการกฎการจัดการ BLOB และการตั้งค่า BLOB อื่น ๆ
type: docs
url: /th/com.aspose.slides/blobmanagementoptions/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

เป็นตัวเลือกที่สามารถใช้จัดการกฎการจัดการ BLOB และการตั้งค่า BLOB อื่น ๆ

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | สร้างตัวเลือกการจัดการ blob เริ่มต้นใหม่ |

## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มาทั้งไฟล์หรือสตรีมได้หรือไม่ตลอดอายุการใช้งานของตัวอย่าง |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มาทั้งไฟล์หรือสตรีมได้หรือไม่ตลอดอายุการใช้งานของตัวอย่าง |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | คุณสมบัตินี้กำหนดว่าจะแจ้งไฟล์ชั่วคราวได้หรือไม่ขณะทำงานกับ BLOB ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | คุณสมบัตินี้กำหนดว่าจะแจ้งไฟล์ชั่วคราวได้หรือไม่ขณะทำงานกับ BLOB ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | กำหนดขนาดรวมสูงสุด (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | กำหนดขนาดรวมสูงสุด (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

สร้างตัวเลือกการจัดการ blob เริ่มต้นใหม่

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มาทั้งไฟล์หรือสตรีมได้หรือไม่ตลอดอายุการใช้งานของตัวอย่าง หากตัวอย่างเป็นเจ้าของ มันจะล็อกแหล่งที่มา ซึ่งช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOB แต่แหล่งที่มา (สตรีมหรือไฟล์) จะไม่สามารถเปลี่ยนแปลงได้ตลอดอายุของ Presentation

**คืนค่า:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มาทั้งไฟล์หรือสตรีมได้หรือไม่ตลอดอายุการใช้งานของตัวอย่าง หากตัวอย่างเป็นเจ้าของ มันจะล็อกแหล่งที่มา ซึ่งช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOB แต่แหล่งที่มา (สตรีมหรือไฟล์) จะไม่สามารถเปลี่ยนแปลงได้ตลอดอายุของ Presentation

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

คุณสมบัตินี้กำหนดว่าจะแจ้งไฟล์ชั่วคราวได้หรือไม่ขณะทำงานกับ BLOB ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์

--------------------

ไฟล์ทั้งหมดจะถูกลบหลังจากการทำงานกับงานนำเสนอเสร็จสิ้น

**คืนค่า:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

คุณสมบัตินี้กำหนดว่าจะแจ้งไฟล์ชั่วคราวได้หรือไม่ขณะทำงานกับ BLOB ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์

--------------------

ไฟล์ทั้งหมดจะถูกลบหลังจากการทำงานกับงานนำเสนอเสร็จสิ้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง ระบบจะใช้ไดเรกทอรีชั่วคราวโดยค่าเริ่มต้น กระบวนการโฮสต์ต้องมีสิทธิ์ในการสร้างไฟล์และโฟลเดอร์ที่นี่

**คืนค่า:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง ระบบจะใช้ไดเรกทอรีชั่วคราวโดยค่าเริ่มต้น กระบวนการโฮสต์ต้องมีสิทธิ์ในการสร้างไฟล์และโฟลเดอร์ที่นี่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

กำหนดขนาดรวมสูงสุด (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOB ทั้งหมดจะถูกโหลดเข้าในหน่วยความจำ; เฉพาะเมื่อถึงขีดจำกัดนี้จึงใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว) การเก็บ BLOB ไว้ในหน่วยความจำช่วยให้ประสิทธิภาพสูงสุดแต่ก็อาจทำให้ใช้หน่วยความจำมาก ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ

--------------------

คุณสมบัตินี้จะถูกละเว้นหาก \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นที่เก็บเดียวที่มีและการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

--------------------

ค่าเริ่มต้นคือ 629,145,600 ไบต์ (600 MB)

--------------------

คุณอาจตั้งค่านี้เป็นศูนย์ แต่จะยังคงสงวนหน่วยความจำขั้นต่ำเล็กน้อยไว้

**คืนค่า:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

กำหนดขนาดรวมสูงสุด (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOB ทั้งหมดจะถูกโหลดเข้าในหน่วยความจำ; เฉพาะเมื่อถึงขีดจำกัดนี้จึงใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว) การเก็บ BLOB ไว้ในหน่วยความจำช่วยให้ประสิทธิภาพสูงสุดแต่ก็อาจทำให้ใช้หน่วยความจำมาก ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ

--------------------

คุณสมบัตินี้จะถูกละเว้นหาก \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นที่เก็บเดียวที่มีและการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

--------------------

ค่าเริ่มต้นคือ 629,145,600 ไบต์ (600 MB)

--------------------

คุณอาจตั้งค่านี้เป็นศูนย์ แต่จะยังคงสงวนหน่วยความจำขั้นต่ำเล็กน้อยไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |