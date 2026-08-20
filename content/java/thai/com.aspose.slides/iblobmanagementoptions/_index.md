---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: วัตถุขนาดใหญ่วัยไบนารี (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นเอนทิตี้เดียว - ตัวอย่างเช่น BLOB สามารถเป็นไฟล์เสียง, วิดีโอ หรือการนำเสนอเองได้.
type: docs
url: /th/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

วัตถุขนาดใหญ่วัยไบนารี (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นเอนทิตี้เดียว - ตัวอย่างเช่น BLOB สามารถเป็นไฟล์เสียง, วิดีโอ หรือการนำเสนอเองได้. มีเทคนิคหลายอย่างที่ใช้เพื่อเพิ่มประสิทธิภาพการใช้หน่วยความจำขณะทำงานกับ BLOBs - ซึ่งอาจถูกจัดเก็บไว้ในงานนำเสนอแล้วหรือจะถูกเพิ่มเข้ามาในภายหลังโดยโปรแกรม การใช้ [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) คุณสามารถเปลี่ยนแง่มุมพฤติกรรมต่าง ๆ เกี่ยวกับการจัดการ BLOBs สำหรับอายุการใช้งานของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation).

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | The root path where temporary files will be created. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | The root path where temporary files will be created. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

คุณสมบัตินี้กำหนดว่าตัวอย่างของ Presentation class สามารถเป็นเจ้าของแหล่งข้อมูล - ไฟล์หรือสตรีม ได้หรือไม่ในช่วงอายุการใช้งานของอินสแตนซ์ หากอินสแตนซ์เป็นเจ้าของ มันจะล็อกแหล่งข้อมูล การทำเช่นนี้ช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งข้อมูล (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ในช่วงอายุการใช้งานของ Presentation นี้ ตัวอย่างเช่น:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException จะถูกโยนขึ้นเนื่องจาก pres.pptx ถูกล็อกตลอดอายุการใช้งานของ Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // หลังจากวัตถุ Presentation ถูกทำลาย ไฟล์จะถูกปลดล็อกและสามารถลบได้
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**คืนค่า:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

คุณสมบัตินี้กำหนดว่าตัวอย่างของ Presentation class สามารถเป็นเจ้าของแหล่งข้อมูล - ไฟล์หรือสตรีม ได้หรือไม่ในช่วงอายุการใช้งานของอินสแตนซ์ หากอินสแตนซ์เป็นเจ้าของ มันจะล็อกแหล่งข้อมูล การทำเช่นนี้ช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งข้อมูล (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ในช่วงอายุการใช้งานของ Presentation นี้ ตัวอย่างเช่น:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException จะถูกโยนขึ้นเนื่องจาก pres.pptx ถูกล็อกตลอดอายุการใช้งานของ Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // หลังจากวัตถุ Presentation ถูกทำลาย ไฟล์จะถูกปลดล็อกและสามารถลบได้
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

คุณสมบัตินี้กำหนดว่ามีการสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOBs หรือไม่ ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์

--------------------

ไฟล์ทั้งหมดจะถูกลบหลังจากการทำงานกับการนำเสนอเสร็จสิ้น

**คืนค่า:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

คุณสมบัตินี้กำหนดว่ามีการสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOBs หรือไม่ ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์

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

เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง ระบบไดเรกทอรีชั่วคราวจะถูกใช้เป็นค่าเริ่มต้น กระบวนการโฮสต์ต้องมีสิทธิ์ในการสร้างไฟล์และโฟลเดอร์ในที่นั้น

**คืนค่า:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง ระบบไดเรกทอรีชั่วคราวจะถูกใช้เป็นค่าเริ่มต้น กระบวนการโฮสต์ต้องมีสิทธิ์ในการสร้างไฟล์และโฟลเดอร์ในที่นั้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

กำหนดขนาดรวมสูงสุด (เป็นไบต์) ที่ BLOBs ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOBs ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกทางเลือก (เช่น ไฟล์ชั่วคราว) การเก็บ BLOBs ในหน่วยความจำช่วยเพิ่มประสิทธิภาพสูงสุดแต่ก็อาจทำให้การใช้หน่วยความจำสูง ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ

--------------------

คุณสมบัตินี้จะถูกละเว้นหาก #isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นที่เก็บข้อมูลเดียวที่มีอยู่และการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

--------------------

ค่าตั้งต้นคือ 629,145,600 ไบต์ (600 MB).

--------------------

คุณอาจตั้งคุณสมบัตินี้เป็นศูนย์ แต่จะยังคงสงวนหน่วยความจำขั้นต่ำจำนวนเล็กน้อยไว้

**คืนค่า:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

กำหนดขนาดรวมสูงสุด (เป็นไบต์) ที่ BLOBs ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOBs ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกทางเลือก (เช่น ไฟล์ชั่วคราว) การเก็บ BLOBs ในหน่วยความจำช่วยเพิ่มประสิทธิภาพสูงสุดแต่ก็อาจทำให้การใช้หน่วยความจำสูง ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ

--------------------

คุณสมบัตินี้จะถูกละเว้นหาก #isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) ถูกตั้งค่าเป็น false เนื่องจากหน่วยความจำจะเป็นที่เก็บข้อมูลเดียวที่มีอยู่และการจำกัดการใช้ BLOB ในหน่วยความจำจะไม่มีผล

--------------------

ค่าตั้งต้นคือ 629,145,600 ไบต์ (600 MB).

--------------------

คุณอาจตั้งคุณสมบัตินี้เป็นศูนย์ แต่จะยังคงสงวนหน่วยความจำขั้นต่ำจำนวนเล็กน้อยไว้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |