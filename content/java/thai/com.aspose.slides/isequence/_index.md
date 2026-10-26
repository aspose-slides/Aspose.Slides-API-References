---
title: ISequence
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แทนคอลเลกชันลำดับของเอฟเฟ็กต์.
type: docs
url: /th/com.aspose.slides/isequence/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

แทนลำดับ (คอลเลกชันของเอฟเฟ็กต์).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | คืนค่าจำนวนเอฟเฟ็กต์ในลำดับ |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | ลบเอฟเฟ็กต์ที่ระบุออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบเอฟเฟ็กต์จากคอลเลกชัน |
| [clear()](#clear--) | ลบเอฟเฟ็กต์ทั้งหมดออกจากคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนค่าเอฟเฟ็กต์ที่ตำแหน่งที่ระบุ |
| [getTriggerShape()](#getTriggerShape--) | คืนค่า หรือ ตั้งค่า shape target สำหรับลำดับ INTERACTIVE |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | คืนค่า หรือ ตั้งค่า shape target สำหรับลำดับ INTERACTIVE |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | ลบเอฟเฟ็กต์สำหรับ shape ที่ระบุ |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | คืนค่าอาร์เรย์ของเอฟเฟ็กต์สำหรับ shape ที่ระบุ |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | คืนค่าอาร์เรย์ของเอฟเฟ็กต์สำหรับย่อหน้าที่ระบุ |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | คืนค่าจำนวนเอฟเฟ็กต์สำหรับ shape ที่ระบุ |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | เพิ่มเอฟเฟ็กต์ใหม่ไปยังส่วนท้ายของลำดับ |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่สำหรับย่อหน้าที่ส่วนท้ายของลำดับ |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | เพิ่มเอฟเฟ็กต์แอนิเมชัน chart ใหม่สำหรับหมวดหมู่หรือซีรีส์ไปยังส่วนท้ายของลำดับ |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | เพิ่มเอฟเฟ็กต์แอนิเมชัน chart ใหม่สำหรับองค์ประกอบในหมวดหมู่หรือซีรีส์ไปยังส่วนท้ายของลำดับ |
### getCount() {#getCount--}
```
public abstract int getCount()
```


คืนค่าจำนวนเอฟเฟ็กต์ในลำดับ. อ่านอย่างเดียว int.

**คืนค่า:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```


ลบเอฟเฟ็กต์ที่ระบุออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | เอฟเฟ็กต์ที่จะลบ |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบเอฟเฟ็กต์จากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเอฟเฟ็กต์ที่จะลบ int |

### clear() {#clear--}
```
public abstract void clear()
```


ลบเอฟเฟ็กต์ทั้งหมดออกจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```


คืนค่าเอฟเฟ็กต์ที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุ [IEffect](../../com.aspose.slides/ieffect) 
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```


คืนค่า หรือ ตั้งค่า shape target สำหรับลำดับ INTERACTIVE. หากลำดับไม่ใช่แบบอินเทอร์แอคทีฟจะคืนค่า null. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```


คืนค่า หรือ ตั้งค่า shape target สำหรับลำดับ INTERACTIVE. หากลำดับไม่ใช่แบบอินเทอร์แอคทีฟจะคืนค่า null. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```


ลบเอฟเฟ็กต์สำหรับ shape ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | วัตถุ Shape [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```


คืนค่าอาร์เรย์ของเอฟเฟ็กต์สำหรับ shape ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | วัตถุ Shape [IShape](../../com.aspose.slides/ishape) |

**คืนค่า:**
com.aspose.slides.IEffect[] - อาร์เรย์ของเอฟเฟ็กต์ [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```


คืนค่าอาร์เรย์ของเอฟเฟ็กต์สำหรับย่อหน้าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | วัตถุ Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |

**คืนค่า:**
com.aspose.slides.IEffect[] - อาร์เรย์ของเอฟเฟ็กต์ [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```


คืนค่าจำนวนเอฟเฟ็กต์สำหรับ shape ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | วัตถุ Shape [IShape](../../com.aspose.slides/ishape) |

**คืนค่า:**
int - จำนวนเอฟเฟ็กต์ int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```


เพิ่มเอฟเฟ็กต์ใหม่ไปยังส่วนท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | วัตถุ Shape [IShape](../../com.aspose.slides/ishape) สำหรับเพิ่มเอฟเฟ็กต์ |
| effectType | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทำงานของเอฟเฟ็กต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุเอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```


เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่สำหรับย่อหน้าที่ส่วนท้ายของลำดับ.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // เลือกย่อหน้าเพื่อเพิ่มเอฟเฟ็กต์
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // เพิ่มเอฟเฟ็กต์แอนิเมชัน Fly ให้กับย่อหน้าที่เลือก
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | วัตถุ Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทำงานของเอฟเฟ็กต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุเอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```


เพิ่มเอฟเฟ็กต์แอนิเมชัน chart ใหม่สำหรับหมวดหมู่หรือซีรีส์ไปยังส่วนท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | วัตถุ Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | ดัชนี int |
| effectType | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทำงานของเอฟเฟ็กต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุเอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```


เพิ่มเอฟเฟ็กต์แอนิเมชัน chart ใหม่สำหรับองค์ประกอบในหมวดหมู่หรือซีรีส์ไปยังส่วนท้ายของลำดับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | วัตถุ Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | ดัชนีของซีรีส์ chart int |
| categoriesIndex | int | ดัชนีของหมวดหมู่ int |
| effectType | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทำงานของเอฟเฟ็กต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - วัตถุเอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)