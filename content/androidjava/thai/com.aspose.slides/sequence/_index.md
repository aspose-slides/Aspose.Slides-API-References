---
title: Sequence
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันลำดับของเอฟเฟกต์.
type: docs
url: /th/com.aspose.slides/sequence/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ใช้งาน:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Represents sequence (collection of effects).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | ส่งคืนจำนวนเอฟเฟกต์ในลำดับ. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | ลบเอฟเฟกต์ที่ระบุจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบเอฟเฟกต์จากคอลเลกชัน. |
| [clear()](#clear--) | ลบเอฟเฟกต์ทั้งหมดจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนเอฟเฟกต์ที่ตำแหน่งที่กำหนด. |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนซ้ำคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด. |
| [getTriggerShape()](#getTriggerShape--) | ส่งคืนหรือกำหนดเป้าหมายรูปแบบสำหรับลำดับ INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | ส่งคืนหรือกำหนดเป้าหมายรูปแบบสำหรับลำดับ INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | ลบเอฟเฟกต์สำหรับรูปแบบที่ระบุ. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | ส่งคืนอาเรย์ของเอฟเฟกต์สำหรับรูปแบบที่ระบุ. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | ส่งคืนอาเรย์ของเอฟเฟกต์สำหรับย่อหน้าที่ระบุ. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | ส่งคืนจำนวนเอฟเฟกต์สำหรับรูปแบบที่ระบุ. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับ. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | เพิ่มเอฟเฟกต์แอนิเมชันใหม่สำหรับย่อหน้าที่ส่วนท้ายของลำดับ. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | เพิ่มเอฟเฟกต์แอนิเมชันชาร์ตใหม่สำหรับหมวดหรือซีรีส์ที่ส่วนท้ายของลำดับ. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | เพิ่มเอฟเฟกต์แอนิเมชันชาร์ตใหม่สำหรับองค์ประกอบในหมวดหรือซีรีส์ที่ส่วนท้ายของลำดับ. |
### getCount() {#getCount--}
```
public final int getCount()
```

ส่งคืนจำนวนเอฟเฟกต์ในลำดับ. อ่านอย่างเดียว int.

**ส่งคืน:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

ลบเอฟเฟกต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | เอฟเฟกต์ที่จะลบ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบเอฟเฟกต์จากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเอฟเฟกต์ที่ควรลบ. |

### clear() {#clear--}
```
public final void clear()
```

ลบเอฟเฟกต์ทั้งหมดจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

ส่งคืนเอฟเฟกต์ที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ. |

**ส่งคืน:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์ [IEffect](../../com.aspose.slides/ieffect).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

ส่งคืน enumerator ที่วนซ้ำคอลเลกชัน.

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำคอลเลกชัน.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

ส่งคืนหรือกำหนดเป้าหมายรูปแบบสำหรับลำดับ INTERACTIVE. หากลำดับไม่เป็น interactive จะส่งคืน null. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**ส่งคืน:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

ส่งคืนหรือกำหนดเป้าหมายรูปแบบสำหรับลำดับ INTERACTIVE. หากลำดับไม่เป็น interactive จะส่งคืน null. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

ลบเอฟเฟกต์สำหรับรูปแบบที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

ส่งคืนอาเรย์ของเอฟเฟกต์สำหรับรูปแบบที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**ส่งคืน:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

ส่งคืนอาเรย์ของเอฟเฟกต์สำหรับย่อหน้าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**ส่งคืน:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

ส่งคืนจำนวนเอฟเฟกต์สำหรับรูปแบบที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**ส่งคืน:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | วัตถุ Shape [IShape](../../com.aspose.slides/ishape) สำหรับเพิ่มเอฟเฟกต์ |
| effectType | int | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทำงานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**ส่งคืน:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุเอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์แอนิเมชันใหม่สำหรับย่อหน้าที่ส่วนท้ายของลำดับ.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // เลือกย่อหน้าที่จะเพิ่มเอฟเฟกต์
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // เพิ่มเอฟเฟกต์แอนิเมชัน Fly ให้กับย่อหน้าที่เลือก
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | วัตถุ Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทำงานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**ส่งคืน:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุเอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์แอนิเมชันชาร์ตใหม่สำหรับหมวดหรือซีรีส์ที่ส่วนท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | วัตถุ Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | ดัชนี int |
| effectType | int | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทำงานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**ส่งคืน:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุเอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์แอนิเมชันชาร์ตใหม่สำหรับองค์ประกอบในหมวดหรือซีรีส์ที่ส่วนท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | วัตถุ Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | ดัชนีของซีรีส์ชาร์ต int |
| categoriesIndex | int | ดัชนีของหมวด int |
| effectType | int | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทำงานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**ส่งคืน:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุเอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)