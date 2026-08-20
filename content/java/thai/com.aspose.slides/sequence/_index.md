---
title: Sequence
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันเอฟเฟ็กต์ในลำดับ.
type: docs
url: /th/com.aspose.slides/sequence/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Represents sequence (collection of effects).

## เมธอด

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | คืนค่าจำนวนเอฟเฟ็กต์ในลำดับ. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | ลบเอฟเฟ็กต์ที่ระบุออกจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบเอฟเฟ็กต์ออกจากคอลเลกชัน. |
| [clear()](#clear--) | ลบเอฟเฟ็กต์ทั้งหมดออกจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | คืนค่าเอฟเฟ็กต์ที่ตำแหน่งที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [getTriggerShape()](#getTriggerShape--) | คืนค่าหรือกำหนด shape target สำหรับลำดับ INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | คืนค่าหรือกำหนด shape target สำหรับลำดับ INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | ลบเอฟเฟ็กต์สำหรับ shape ที่ระบุ. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | คืนค่า array ของเอฟเฟ็กต์สำหรับ shape ที่ระบุ. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | คืนค่า array ของเอฟเฟ็กต์สำหรับ paragraph ที่ระบุ. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | คืนค่าจำนวนเอฟเฟ็กต์สำหรับ shape ที่ระบุ. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | เพิ่มเอฟเฟ็กต์ใหม่ไปที่ท้ายลำดับ. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่สำหรับ paragraph ไปที่ท้ายลำดับ. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | เพิ่มเอฟเฟ็กต์แอนิเมชันของแผนภูมิใหม่สำหรับหมวดหรือซีรีส์ไปที่ท้ายลำดับ. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | เพิ่มเอฟเฟ็กต์แอนิเมชันของแผนภูมิใหม่สำหรับองค์ประกอบในหมวดหรือซีรีส์ไปที่ท้ายลำดับ. |

### getCount() {#getCount--}
```
public final int getCount()
```

คืนค่าจำนวนเอฟเฟ็กต์ในลำดับ อ่านอย่างเดียว int.

**คืนค่า:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

ลบเอฟเฟ็กต์ที่ระบุออกจากคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | เอฟเฟ็กต์ที่จะลบ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบเอฟเฟ็กต์ออกจากคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของเอฟเฟ็กต์ที่ควรลบ. |

### clear() {#clear--}
```
public final void clear()
```

ลบเอฟเฟ็กต์ทั้งหมดออกจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

คืนค่าเอฟเฟ็กต์ที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ. |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์ [IEffect](../../com.aspose.slides/ieffect).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - IGenericEnumerator ที่สามารถใช้วนซ้ำผ่านคอลเลกชัน.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

คืนค่าหรือกำหนด shape target สำหรับลำดับ INTERACTIVE หากลำดับไม่ใช่ interactive จะคืนค่า null. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

คืนค่าหรือกำหนด shape target สำหรับลำดับ INTERACTIVE หากลำดับไม่ใช่ interactive จะคืนค่า null. อ่าน/เขียน [IShape](../../com.aspose.slides/ishape).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

ลบเอฟเฟ็กต์สำหรับ shape ที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

คืนค่า array ของเอฟเฟ็กต์สำหรับ shape ที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**คืนค่า:**
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

คืนค่า array ของเอฟเฟ็กต์สำหรับ paragraph ที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**คืนค่า:**
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

คืนค่าจำนวนเอฟเฟ็กต์สำหรับ shape ที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**คืนค่า:**
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟ็กต์ใหม่ไปที่ท้ายลำดับ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | อ็อบเจ็กต์ Shape [IShape](../../com.aspose.slides/ishape) สำหรับเพิ่มเอฟเฟ็กต์ |
| effectType | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทริกเกอร์ของเอฟเฟ็กต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟ็กต์แอนิเมชันใหม่สำหรับ paragraph ไปที่ท้ายลำดับ.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // เลือกย่อหน้าเพื่อเพิ่มเอฟเฟกต์
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // เพิ่มเอฟเฟ็กต์แอนิเมชัน Fly ให้กับย่อหน้าที่เลือก
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | อ็อบเจ็กต์ Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทริกเกอร์ของเอฟเฟ็กต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟ็กต์แอนิเมชันของแผนภูมิใหม่สำหรับหมวดหรือซีรีส์ไปที่ท้ายลำดับ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | อ็อบเจ็กต์ Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | ดัชนี int |
| effectType | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทริกเกอร์ของเอฟเฟ็กต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟ็กต์แอนิเมชันของแผนภูมิใหม่สำหรับองค์ประกอบในหมวดหรือซีรีส์ไปที่ท้ายลำดับ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | อ็อบเจ็กต์ Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | ดัชนีของซีรีส์แผนภูมิ int |
| categoriesIndex | int | ดัชนีของหมวดหมู่ int |
| effectType | int | ประเภทของเอฟเฟ็กต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟ็กต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการทริกเกอร์ของเอฟเฟ็กต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟ็กต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)