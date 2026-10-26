---
title: ISectionCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของส่วน.
type: docs
url: /th/com.aspose.slides/isectioncollection/
---
**ส่วนต่อประสานทั้งหมดที่ทำการใช้งาน:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

แสดงคอลเลกชันของส่วน
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | เพิ่มส่วนใหม่ที่เริ่มจากสไลด์เฉพาะ |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | เพิ่มส่วนเปล่าที่ตำแหน่งที่ระบุของคอลเลกชัน |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | ลบส่วนและสไลด์ที่อยู่ในส่วนนั้น |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | ลบส่วน |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | ย้ายส่วนและสไลด์ของมันจากคอลเลกชันไปยังตำแหน่งที่ระบุ |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | เพิ่มส่วนเปล่าที่ปลายของคอลเลกชัน |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | คืนค่าดัชนีของส่วนที่ระบุในคอลเลกชัน |
| [clear()](#clear--) | ลบส่วนทั้งหมดจากคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [ISection](../../com.aspose.slides/isection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

เพิ่มส่วนใหม่ที่เริ่มจากสไลด์เฉพาะ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์แรกของส่วน |

**ผลลัพธ์:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่ม

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

เพิ่มส่วนเปล่าที่ตำแหน่งที่ระบุของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |
| index | int | ดัชนีของส่วนใหม่ |

**ผลลัพธ์:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่ม

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

ลบส่วนและสไลด์ที่อยู่ในส่วนนั้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่จะลบออกจากคอลเลกชัน |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

ลบส่วน สไลด์ที่อยู่ในส่วนจะถูกรวมเข้ากับส่วนก่อนหน้า

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่จะลบออกจากคอลเลกชัน |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

ย้ายส่วนและสไลด์ของมันจากคอลเลกชันไปยังตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่จะย้าย |
| index | int | ดัชนีเป้าหมาย |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

เพิ่มส่วนเปล่าที่ปลายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |

**ผลลัพธ์:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่ม

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

คืนค่าดัชนีของส่วนที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่จะค้นหา |

**ผลลัพธ์:**
int - ดัชนีของส่วนหรือ -1 หากส่วนไม่ได้มาจากคอลเลกชันนี้

### clear() {#clear--}
```
public abstract void clear()
```

ลบส่วนทั้งหมดจากคอลเลกชัน