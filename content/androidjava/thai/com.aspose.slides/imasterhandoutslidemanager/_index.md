---
title: IMasterHandoutSlideManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ตัวจัดการสไลด์สรุปหลัก.
type: docs
url: /th/com.aspose.slides/imasterhandoutslidemanager/
---```
public interface IMasterHandoutSlideManager
```

ตัวจัดการสไลด์สรุปหลัก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getMasterHandoutSlide()](#getMasterHandoutSlide--) | Returns a master for all notes slides of this presentation if there is one, otherwise returns null. |
| [setDefaultMasterHandoutSlide()](#setDefaultMasterHandoutSlide--) | Sets default master handout slide to related handout slide. |
| [removeMasterHandoutSlide()](#removeMasterHandoutSlide--) | Removes master handout slide. |
### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide getMasterHandoutSlide()
```

คืนค่ามาสเตอร์สำหรับสไลด์บันทึกทั้งหมดของการนำเสนอนี้หากมี, มิฉะนั้นจะคืนค่า null. อ่านอย่างเดียว [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide).

**คืนค่า:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### setDefaultMasterHandoutSlide() {#setDefaultMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide setDefaultMasterHandoutSlide()
```

ตั้งค่าสไลด์สรุปหลักเริ่มต้นให้กับสไลด์สรุปที่เกี่ยวข้อง.

**คืนค่า:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide) - สไลด์สรุปหลัก [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### removeMasterHandoutSlide() {#removeMasterHandoutSlide--}
```
public abstract void removeMasterHandoutSlide()
```

ลบสไลด์สรุปหลัก.