---
title: BlobManagementOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนตัวเลือกที่สามารถใช้เพื่อจัดการกฎการจัดการ BLOB และการตั้งค่า BLOB อื่น ๆ
type: docs
url: /th/com.aspose.slides/blobmanagementoptions/
---
**สืบทอด:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

แทนตัวเลือกที่สามารถใช้เพื่อจัดการกฎการจัดการ BLOB และการตั้งค่า BLOB อื่น ๆ

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | สร้างตัวเลือกการจัดการ blob เริ่มต้นใหม่ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มาของไฟล์หรือสตรีมได้หรือไม่ตลอดอายุของตัวอย่าง |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มาของไฟล์หรือสตรีมได้หรือไม่ตลอดอายุของตัวอย่าง |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | คุณสมบัตินี้กำหนดว่าจำเป็นต้องสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOB หรือไม่ ซึ่งจะช่วยลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | คุณสมบัตินี้กำหนดว่าจำเป็นต้องสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOB หรือไม่ ซึ่งจะช่วยลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

สร้างตัวเลือกการจัดการ blob เริ่มต้นใหม่

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มาของไฟล์หรือสตรีมได้หรือไม่ตลอดอายุของตัวอย่าง หากเป็นเจ้าของ จะทำการล็อคแหล่งที่มา ซึ่งช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOB แต่แหล่งที่มา (สตรีมหรือไฟล์) จะไม่สามารถเปลี่ยนแปลงได้ตลอดอายุของ Presentation

**คืนค่า:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มาของไฟล์หรือสตรีมได้หรือไม่ตลอดอายุของตัวอย่าง หากเป็นเจ้าของ จะทำการล็อคแหล่งที่มา ซึ่งช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOB แต่แหล่งที่มา (สตรีมหรือไฟล์) จะไม่สามารถเปลี่ยนแปลงได้ตลอดอายุของ Presentation

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

คุณสมบัตินี้กำหนดว่าจำเป็นต้องสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOB หรือไม่ ซึ่งจะช่วยลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์

--------------------

ไฟล์ทั้งหมดจะถูกลบหลังจากเสร็จสิ้นการทำงานกับงานนำเสนอ

**คืนค่า:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

คุณสมบัตินี้กำหนดว่าจำเป็นต้องสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOB หรือไม่ ซึ่งจะช่วยลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์

--------------------

ไฟล์ทั้งหมดจะถูกลบหลังจากเสร็จสิ้นการทำงานกับงานนำเสนอ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น โดยค่าเริ่มต้นจะใช้ไดเรกทอรีชั่วคราวของระบบ กระบวนการโฮสต์ต้องมีสิทธิ์ในการสร้างไฟล์และโฟลเดอร์ในตำแหน่งนี้

**คืนค่า:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น โดยค่าเริ่มต้นจะใช้ไดเรกทอรีชั่วคราวของระบบ กระบวนการโฮสต์ต้องมีสิทธิ์ในการสร้างไฟล์และโฟลเดอร์ในตำแหน่งนี้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOB ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว) การเก็บ BLOB ในหน่วยความจำช่วยเพิ่มประสิทธิภาพสูงสุดแต่ทำให้การใช้หน่วยความจำสูง ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ

--------------------

คุณสมบัตินี้จะถูกละเลยหาก \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นตำแหน่งจัดเก็บเดียวที่มีอยู่และการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

--------------------

ค่าเริ่มต้นคือ 629,145,600 ไบต์ (600 MB)

--------------------

คุณอาจตั้งค่าคุณสมบัตินี้เป็นศูนย์ได้ แต่จะยังคงสงวนหน่วยความจำขั้นต่ำจำนวนเล็กน้อยไว้

**คืนค่า:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOB ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว) การเก็บ BLOB ในหน่วยความจำช่วยเพิ่มประสิทธิภาพสูงสุดแต่ทำให้การใช้หน่วยความจำสูง ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ

--------------------

คุณสมบัตินี้จะถูกละเลยหาก \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นตำแหน่งจัดเก็บเดียวที่มีอยู่และการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

--------------------

ค่าเริ่มต้นคือ 629,145,600 ไบต์ (600 MB)

--------------------

คุณอาจตั้งค่าคุณสมบัตินี้เป็นศูนย์ได้ แต่จะยังคงสงวนหน่วยความจำขั้นต่ำจำนวนเล็กน้อยไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |