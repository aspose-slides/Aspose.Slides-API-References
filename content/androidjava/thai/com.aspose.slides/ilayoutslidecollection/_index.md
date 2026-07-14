---
title: ILayoutSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคลาสฐานสำหรับคอลเลกชันของสไลด์เค้าโครง.
type: docs
url: /th/com.aspose.slides/ilayoutslidecollection/
---
**ส่วนต่อประสานที่ดำเนินการทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

เป็นคลาสฐานสำหรับคอลเลกชันของสไลด์เค้าโครง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนสไลด์เค้าโครงตามดัชนี. |
| [getByType(byte type)](#getByType-byte-) | ส่งคืนสไลด์เค้าโครงแรกของประเภทที่ระบุ. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | ลบเค้าโครงออกจากคอลเลกชัน. |
| [removeUnused()](#removeUnused--) | ลบสไลด์เค้าโครงที่ไม่ได้ใช้ (สไลด์เค้าโครงที่ HasDependingSlides เป็น false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


ส่งคืนสไลด์เค้าโครงตามดัชนี อ่านอย่างเดียว [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


ส่งคืนสไลด์เค้าโครงแรกของประเภทที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | byte | ประเภทของสไลด์เค้าโครงที่ต้องการค้นหา. |

**ค่าที่ส่งคืน:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) ที่มีประเภทที่ระบุหรือ null หากไม่พบเค้าโครง
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


ลบเค้าโครงออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์เค้าโครงที่จะลบออกจากคอลเลกชัน.

--------------------
1) เพื่อลดการเกิด PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของเค้าโครงก่อน. 2) คุณยังสามารถใช้เมธอด [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) เพื่อทำให้โค้ดง่ายขึ้น. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


ลบสไลด์เค้าโครงที่ไม่ได้ใช้ (สไลด์เค้าโครงที่ HasDependingSlides เป็น false).