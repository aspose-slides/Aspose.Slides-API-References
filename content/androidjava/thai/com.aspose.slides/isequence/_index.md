---
title: ISequence
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันลำดับของเอฟเฟกต์.
type: docs
url: /th/com.aspose.slides/isequence/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

เป็นตัวแทนของลำดับ (คอลเลกชันของเอฟเฟกต์).

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | คืนจำนวนเอฟเฟกต์ในลำดับ. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | ลบเอฟเฟกต์ที่ระบุจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบเอฟเฟกต์จากคอลเลกชัน. |
| [clear()](#clear--) | ลบเอฟเฟกต์ทั้งหมดจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | คืนเอฟเฟกต์ที่ตำแหน่งที่ระบุ. |
| [getTriggerShape()](#getTriggerShape--) | คืนหรือกำหนดเป้าหมายรูปร่างสำหรับลำดับ INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | คืนหรือกำหนดเป้าหมายรูปร่างสำหรับลำดับ INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | ลบเอฟเฟกต์สำหรับรูปร่างที่ระบุ. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | คืนอาร์เรย์ของเอฟเฟกต์สำหรับรูปร่างที่ระบุ. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | คืนอาร์เรย์ของเอฟเฟกต์สำหรับย่อหน้าที่ระบุ. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | คืนจำนวนของเอฟเฟกต์สำหรับรูปร่างที่ระบุ. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | เพิ่มเอฟเฟกต์ใหม่ไปยังตำแหน่งสุดท้ายของลำดับ. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | เพิ่มเอฟเฟกต์การเคลื่อนไหวใหม่สำหรับย่อหน้าที่ตำแหน่งสุดท้ายของลำดับ. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | เพิ่มเอฟเฟกต์การเคลื่อนไหวแผนภูมิใหม่สำหรับประเภทหรือชุดข้อมูลไปยังตำแหน่งสุดท้ายของลำดับ. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | เพิ่มเอฟเฟกต์การเคลื่อนไหวแผนภูมิใหม่สำหรับองค์ประกอบในประเภทหรือชุดข้อมูลไปยังตำแหน่งสุดท้ายของลำดับ. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

คืนจำนวนเอฟเฟกต์ในลำดับ. อ่านอย่างเดียว int.

**คืนค่า:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

ลบเอฟเฟกต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | เอฟเฟกต์ที่ต้องการลบ. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบเอฟเฟกต์จากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของเอฟเฟกต์ที่ต้องการลบ |

### clear() {#clear--}
```
public abstract void clear()
```

ลบเอฟเฟกต์ทั้งหมดจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

คืนเอฟเฟกต์ที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งขององค์ประกอบ. |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) อ็อบเจ็กต์

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

คืนหรือกำหนดเป้าหมายรูปร่างสำหรับลำดับ INTERACTIVE. หากลำดับไม่ใช่แบบอินเทอร์แอคทีฟจะคืนค่า null. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

คืนหรือกำหนดเป้าหมายรูปร่างสำหรับลำดับ INTERACTIVE. หากลำดับไม่ใช่แบบอินเทอร์แอคทีฟจะคืนค่า null. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

ลบเอฟเฟกต์สำหรับรูปร่างที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | วัตถุรูปร่าง [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

คืนอาร์เรย์ของเอฟเฟกต์สำหรับรูปร่างที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | อ็อบเจ็กต์รูปร่าง [IShape](../../com.aspose.slides/ishape) |

**คืนค่า:**
com.aspose.slides.IEffect[] - อาร์เรย์ของเอฟเฟกต์ [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

คืนอาร์เรย์ของเอฟเฟกต์สำหรับย่อหน้าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | อ็อบเจ็กต์ย่อหน้า [IParagraph](../../com.aspose.slides/iparagraph) |

**คืนค่า:**
com.aspose.slides.IEffect[] - อาร์เรย์ของเอฟเฟกต์ [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

คืนจำนวนของเอฟเฟกต์สำหรับรูปร่างที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | อ็อบเจ็กต์รูปร่าง [IShape](../../com.aspose.slides/ishape) |

**คืนค่า:**
int - จำนวนของเอฟเฟกต์ int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์ใหม่ไปยังตำแหน่งสุดท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | อ็อบเจ็กต์รูปร่าง [IShape](../../com.aspose.slides/ishape) สำหรับเพิ่มเอฟเฟกต์ |
| effectType | int | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการเรียกใช้งานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์การเคลื่อนไหวใหม่สำหรับย่อหน้าที่ตำแหน่งสุดท้ายของลำดับ.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // เลือกย่อหน้าที่จะเพิ่มเอฟเฟกต์
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // เพิ่มเอฟเฟกต์การเคลื่อนไหว Fly ให้กับย่อหน้าที่เลือก
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | อ็อบเจ็กต์ย่อหน้า [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการเรียกใช้งานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์การเคลื่อนไหวแผนภูมิใหม่สำหรับประเภทหรือชุดข้อมูลไปยังตำแหน่งสุดท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | อ็อบเจ็กต์แผนภูมิ [IChart](../../com.aspose.slides/ichart) |
| type | int | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | ตำแหน่ง int |
| effectType | int | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการเรียกใช้งานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์การเคลื่อนไหวแผนภูมิใหม่สำหรับองค์ประกอบในประเภทหรือชุดข้อมูลไปยังตำแหน่งสุดท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | อ็อบเจ็กต์แผนภูมิ [IChart](../../com.aspose.slides/ichart) |
| type | int | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | ตำแหน่งของชุดข้อมูลแผนภูมิ int |
| categoriesIndex | int | ตำแหน่งของประเภท int |
| effectType | int | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการเรียกใช้งานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)