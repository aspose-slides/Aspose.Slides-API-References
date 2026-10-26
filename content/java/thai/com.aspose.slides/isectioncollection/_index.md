---
title: ISectionCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นคอลเลกชันของส่วน
type: docs
url: /th/com.aspose.slides/isectioncollection/
---
**ส่วนต่อประสานที่ดำเนินการทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

เป็นคอลเลกชันของส่วน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งที่กำหนด |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | เพิ่มส่วนใหม่ที่เริ่มจากสไลด์เฉพาะ |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | เพิ่มส่วนว่างในตำแหน่งที่ระบุของคอลเลกชัน |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | ลบส่วนและสไลด์ที่อยู่ในส่วนนั้น |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | ลบส่วน |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | ย้ายส่วนและสไลด์ของมันจากคอลเลกชันไปยังตำแหน่งที่ระบุ |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | เพิ่มส่วนว่างที่ส่วนท้ายของคอลเลกชัน |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | ส่งคืนดัชนีของส่วนที่ระบุในคอลเลกชัน |
| [clear()](#clear--) | ลบส่วนทั้งหมดออกจากคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

ดึงองค์ประกอบที่ตำแหน่งที่กำหนด. อ่านอย่างเดียว [ISection](../../com.aspose.slides/isection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

เพิ่มส่วนใหม่ที่เริ่มจากสไลด์เฉพาะ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์แรกของส่วน |

**คืนค่า:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่ม

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

เพิ่มส่วนว่างในตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |
| index | int | ดัชนีของส่วนใหม่ |

**คืนค่า:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่ม

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

ลบส่วนและสไลด์ที่อยู่ในส่วนนั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการลบออกจากคอลเลกชัน |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

ลบส่วน. สไลด์ที่อยู่ในส่วนจะถูกรวมเข้ากับส่วนก่อนหน้า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการลบออกจากคอลเลกชัน |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

ย้ายส่วนและสไลด์ของมันจากคอลเลกชันไปยังตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการย้าย |
| index | int | ดัชนีเป้าหมาย |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

เพิ่มส่วนว่างที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |

**คืนค่า:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่ม

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

ส่งคืนดัชนีของส่วนที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการค้นหา |

**คืนค่า:**
int - ดัชนีของส่วนหรือ -1 หากส่วนไม่อยู่ในคอลเลกชันนี้

### clear() {#clear--}
```
public abstract void clear()
```

ลบส่วนทั้งหมดออกจากคอลเลกชัน.