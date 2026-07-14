---
title: IBlobManagementOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: Binary Large Object (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นเอกเทศเดียว - เช่น BLOB สามารถเป็นเสียง วิดีโอ หรือการนำเสนอเอง
type: docs
url: /th/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Binary Large Object (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นเอกเทศเดียว - เช่น BLOB สามารถเป็นเสียง วิดีโอ หรือการนำเสนอเอง เทคนิคหลายอย่างถูกใช้เพื่อเพิ่มประสิทธิภาพการใช้หน่วยความจำขณะทำงานกับ BLOBs - ซึ่งอาจถูกเก็บไว้แล้วในงานนำเสนอหรือเพิ่มในภายหลังด้วยโปรแกรม การใช้ [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) คุณสามารถเปลี่ยนพฤติกรรมต่าง ๆ ที่เกี่ยวกับการจัดการ BLOBs สำหรับอายุการใช้งานของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ได้

## Methods

| Method | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | คุณสมบัตินี้กำหนดว่อินสแตนซ์ของคลาส Presentation สามารถเป็นเจ้าของแหล่งข้อมูล - ไฟล์หรือสตรีมตลอดอายุการใช้งานของอินสแตนซ์ได้หรือไม่ |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | คุณสมบัตินี้กำหนดว่อินสแตนซ์ของคลาส Presentation สามารถเป็นเจ้าของแหล่งข้อมูล - ไฟล์หรือสตรีมตลอดอายุการใช้งานของอินสแตนซ์ได้หรือไม่ |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | คุณสมบัตินี้กำหนดว่าสามารถสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOBs ได้หรือไม่ ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | คุณสมบัตินี้กำหนดว่าสามารถสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOBs ได้หรือไม่ ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOBs ทั้งหมดอาจใช้ในหน่วยความจำ |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOBs ทั้งหมดอาจใช้ในหน่วยความจำ |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

คุณสมบัตินี้กำหนดว่อินสแตนซ์ของคลาส Presentation สามารถเป็นเจ้าของแหล่งข้อมูล - ไฟล์หรือสตรีมตลอดอายุการใช้งานของอินสแตนซ์ได้หรือไม่ หากอินสแตนซ์เป็นเจ้าของ มันจะล็อกแหล่งข้อมูล ซึ่งช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งข้อมูล (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ตลอดอายุการใช้งานของอินสแตนซ์ Presentation นี่คือตัวอย่าง:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // จะเกิด IOException เนื่องจาก pres.pptx ถูกล็อกตลอดอายุการใช้งานของ Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // หลังจากอ็อบเจกต์ Presentation ถูกทำลาย ไฟล์จะถูกปลดล็อกและสามารถลบได้
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**คืนค่า:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

คุณสมบัตินี้กำหนดว่อินสแตนซ์ของคลาส Presentation สามารถเป็นเจ้าของแหล่งข้อมูล - ไฟล์หรือสตรีมตลอดอายุการใช้งานของอินสแตนซ์ได้หรือไม่ หากอินสแตนซ์เป็นเจ้าของ มันจะล็อกแหล่งข้อมูล ซึ่งช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งข้อมูล (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ตลอดอายุการใช้งานของอินสแตนซ์ Presentation นี่คือตัวอย่าง:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // จะเกิด IOException เพราะ pres.pptx ถูกล็อกตลอดอายุการใช้งานของ Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // หลังจากอ็อบเจกต์ Presentation ถูกทำลาย ไฟล์จะถูกปลดล็อกและสามารถลบได้
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

คุณสมบัตินี้กำหนดว่าสามารถสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOBs ได้หรือไม่ ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์

--------------------

ไฟล์ทั้งหมดจะถูกลบหลังจากการทำงานกับการนำเสนอเสร็จสิ้น

**คืนค่า:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

คุณสมบัตินี้กำหนดว่าสามารถสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOBs ได้หรือไม่ ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์

--------------------

ไฟล์ทั้งหมดจะถูกลบหลังจากการทำงานกับการนำเสนอเสร็จสิ้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น ระบบจะใช้ไดเรกทอรีชั่วคราวของระบบเป็นค่าเริ่มต้น กระบวนการโฮสต์ควรมีสิทธิ์ในการสร้างไฟล์และโฟลเดอร์ที่นั่น

**คืนค่า:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้างขึ้น ระบบจะใช้ไดเรกทอรีชั่วคราวของระบบเป็นค่าเริ่มต้น กระบวนการโฮสต์ควรมีสิทธิ์ในการสร้างไฟล์และโฟลเดอร์ที่นั่น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOBs ทั้งหมดอาจใช้ในหน่วยความจำ ตามค่าเริ่มต้น BLOBs ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อขีดจำกัดนี้ถึงจะใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว) การเก็บ BLOBs ในหน่วยความจำเพิ่มประสิทธิภาพสูงสุดแต่สามารถทำให้การใช้หน่วยความจำสูงได้ ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ

--------------------

คุณสมบัตินี้จะถูกละเว้นหาก \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นที่เก็บเดียวและการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

--------------------

ค่าตั้งต้นคือ 629,145,600 ไบต์ (600 MB)

--------------------

คุณอาจตั้งค่าคุณสมบัตินี้เป็นศูนย์ แต่จะยังคงสงวนพื้นที่หน่วยความจำขั้นต่ำจำนวนเล็กน้อยไว้

**คืนค่า:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOBs ทั้งหมดอาจใช้ในหน่วยความจำ ตามค่าเริ่มต้น BLOBs ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อขีดจำกัดนี้ถึงจะใช้กลไกทางเลือก (เช่นไฟล์ชั่วคราว) การเก็บ BLOBs ในหน่วยความจำเพิ่มประสิทธิภาพสูงสุดแต่สามารถทำให้การใช้หน่วยความจำสูงได้ ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ

--------------------

คุณสมบัตินี้จะถูกละเว้นหาก \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นที่เก็บเดียวและการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

--------------------

ค่าตั้งต้นคือ 629,145,600 ไบต์ (600 MB)

--------------------

คุณอาจตั้งค่าคุณสมบัตินี้เป็นศูนย์ แต่จะยังคงสงวนพื้นที่หน่วยความจำขั้นต่ำจำนวนเล็กน้อยไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |