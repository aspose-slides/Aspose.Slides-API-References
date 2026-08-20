---
title: IMasterSlideCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงคอลเลกชันของสไลด์มาสเตอร์.
type: docs
url: /th/com.aspose.slides/imasterslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

แสดงถึงคอลเลกชันของสไลด์มาสเตอร์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุจากคอลเลกชัน |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | ลบสไลด์มาสเตอร์ที่ไม่ได้ใช้ |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | เพิ่มสำเนาของสไลด์มาสเตอร์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | แทรกสำเนาของสไลด์มาสเตอร์ที่ระบุไปยังตำแหน่งที่กำหนดในคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [IMasterSlide](../../com.aspose.slides/imasterslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์มาสเตอร์ที่จะลบจากคอลเลกชัน |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบองค์ประกอบที่ตำแหน่งที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่จะลบ |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


ลบสไลด์มาสเตอร์ที่ไม่ได้ใช้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ignorePreserveField | boolean | กำหนดว่าควรลบมาสเตอร์ที่ไม่ได้ใช้แม้ว่า property [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) ของมันจะตั้งค่าเป็น true หรือไม่ |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


เพิ่มสำเนาของสไลด์มาสเตอร์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. สไลด์เค้าโครงที่เชื่อมโยงจะถูกคัดลอกด้วยเช่นกัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์ที่จะทำสำเนา |

**ผลลัพธ์:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - สไลด์ที่เพิ่ม.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


แทรกสำเนาของสไลด์มาสเตอร์ที่ระบุไปยังตำแหน่งที่กำหนดในคอลเลกชัน. สไลด์เค้าโครงที่เชื่อมโยงจะถูกคัดลอกด้วยเช่นกัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่ |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์ที่จะทำสำเนา |

**ผลลัพธ์:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - สไลด์มาสเตอร์ที่แทรก.