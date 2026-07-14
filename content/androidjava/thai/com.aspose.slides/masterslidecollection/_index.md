---
title: MasterSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของสไลด์แม่
type: docs
url: /th/com.aspose.slides/masterslidecollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำตามทั้งหมด:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

เป็นคอลเลกชันของสไลด์แม่.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | ลบการเกิดครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | ลบสไลด์แม่ที่ไม่ได้ใช้ |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | เพิ่มสำเนาของสไลด์แม่ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | แทรกสำเนาของสไลด์แม่ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากฐานการซิงโครไนซ์ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า iterator ของ Java สำหรับคอลเลกชันทั้งหมด |
### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [MasterSlide](../../com.aspose.slides/masterslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

ลบการเกิดครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์แม่ที่ต้องการลบจากคอลเลกชัน |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ขององค์ประกอบที่ต้องการลบ |

--------------------

เพื่อหลีกเลี่ยงการโยงข้อยกเว้น PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของ master ก่อน. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

ลบสไลด์แม่ที่ไม่ได้ใช้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ignorePreserveField | boolean | กำหนดว่าควิธีการนี้ควรลบ master ที่ไม่ได้ใช้แม้ว่าคุณสมบัติ [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) ของมันจะถูกตั้งเป็น true หรือไม่ |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

เพิ่มสำเนาของสไลด์แม่ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน สไลด์เลย์เอาต์ที่เชื่อมโยงจะถูกคัดลอกด้วย.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์ที่ต้องการคัดลอก |

**คืนค่า:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - สไลด์ที่เพิ่ม
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

แทรกสำเนาของสไลด์แม่ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน สไลด์เลย์เอาต์ที่เชื่อมโยงจะถูกคัดลอกด้วย.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation เพื่อโหลดไฟล์งานนำเสนอต้นทาง
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // สร้างอินสแตนซ์ของคลาส Presentation สำหรับงานนำเสนอปลายทาง (ที่สไลด์จะถูกคัดลอก)
>      Presentation destPres = new Presentation();
>      try {
>          // สร้างอินสแตนซ์ของ ISlide จากคอลเลกชันสไลด์ในงานนำเสนอต้นทางพร้อมกับ
>          // สไลด์แม่
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // ดึงสไลด์แม่ของงานนำเสนอปลายทาง
>          IMasterSlideCollection masters = destPres.getMasters();
>          // คัดลอกสไลด์แม่ที่ต้องการจากงานนำเสนอต้นทางไปยังคอลเลกชันของสไลด์แม่ใน
>          // งานนำเสนอปลายทาง
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // คอลเลกชันของสไลด์ในงานนำเสนอปลายทาง
>          ISlideCollection slds = destPres.getSlides();
>          // คัดลอกสไลด์ต้นทางไปยังคอลเลกชันสไลด์ปลายทาง.
>          slds.addClone(SourceSlide, iSlide, true);
>          // บันทึกงานนำเสนอปลายทางลงดิสก์
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่ |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์ที่ต้องการคัดลอก |

**คืนค่า:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - สไลด์แม่ที่แทรก
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากฐานการซิงโครไนซ์ อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - ตัว IGenericEnumerator ที่สามารถใช้ในการวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

คืนค่า iterator ของ Java สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - ตัว java.util.Iterator สำหรับคอลเลกชันทั้งหมด