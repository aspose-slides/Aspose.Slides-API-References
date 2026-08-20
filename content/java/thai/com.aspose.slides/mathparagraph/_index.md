---
title: MathParagraph
second_title: Aspose.Slides สำหรับ Java API อ้างอิง
description: ย่อหน้าทางคณิตศาสตร์ที่เป็นคอนเทนเนอร์สำหรับบล็อกทางคณิตศาสตร์ IMathBlock
type: docs
url: /th/com.aspose.slides/mathparagraph/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

ย่อหน้าทางคณิตศาสตร์ที่เป็นคอนเทนเนอร์สำหรับบล็อกทางคณิตศาสตร์ (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathParagraph. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathParagraph. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Default value: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Default value: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | ส่งคืนวัตถุ Parent_Immediate. |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่จริง ๆ แล้วอยู่ในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับรายการที่ตำแหน่งที่ระบุ. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | รับรายการที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบองค์ประกอบทั้งหมดจากคอลเลกชัน. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | เพิ่ม IMathBlock ไปยังท้ายของคอลเลกชัน. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | กำหนดดัชนีของ IMathBlock ที่ระบุในคอลเลกชัน. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | แทรก IMathBlock ไปยังคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบรายการที่ตำแหน่งที่ระบุจากคอลเลกชัน. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | บันทึกเนื้อหาของ [MathParagraph](../../com.aspose.slides/mathparagraph) นี้เป็น MathML |
| [toLatex()](#toLatex--) | รับสมการทางคณิตศาสตร์ในรูปแบบ LaTeX |

### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
> ```

### MathParagraph(IMathBlock mathBlock) {#MathParagraph-com.aspose.slides.IMathBlock-}
```
public MathParagraph(IMathBlock mathBlock)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

Paragraph Justification Default value: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**ส่งคืน:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

Paragraph Justification Default value: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนวัตถุ Parent_Immediate. อ่านแบบอย่างเดียว IDOMObject.

**ส่งคืน:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนขององค์ประกอบที่จริง ๆ แล้วอยู่ในคอลเลกชัน. อ่านแบบอย่างเดียว int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**ส่งคืน:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

รับรายการที่ตำแหน่งที่ระบุ. อ่านแบบอย่างเดียว [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่ต้องการรับ |

**ส่งคืน:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกของข้อความทางคณิตศาสตร์.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

รับรายการที่ตำแหน่งที่ระบุ. อ่านแบบอย่างเดียว [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่ต้องการรับ |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกของข้อความทางคณิตศาสตร์. |

### clear() {#clear--}
```
public final void clear()
```

ลบองค์ประกอบทั้งหมดจากคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
> ```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```

เพิ่ม IMathBlock ไปยังท้ายของคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกทางคณิตศาสตร์ที่จะถูกเพิ่มไปยังท้ายของคอลเลกชัน |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | อ็อบเจ็กต์ที่ต้องการลบจากคอลเลกชัน. |

**ส่งคืน:**
boolean - true หาก mathBlock ถูกลบสำเร็จจากคอลเลกชัน; มิฉะนั้น false. เมธอดนี้ยังคืนค่า false หากไม่พบ mathBlock ในคอลเลกชันดั้งเดิม.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | อ็อบเจ็กต์ที่ต้องการค้นหาในคอลเลกชัน. |

**ส่งคืน:**
boolean - true หาก mathBlock พบในคอลเลกชัน; มิฉะนั้น false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

กำหนดดัชนีของ IMathBlock ที่ระบุในคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | รายการที่ต้องการค้นหาในคอลเลกชัน. |

**ส่งคืน:**
int - ดัชนีของ mathBlock หากพบในคอลเลกชัน; มิฉะนั้น -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

แทรก IMathBlock ไปยังคอลเลกชันที่ตำแหน่งที่ระบุ.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ต้องการแทรกรายการ. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock ที่ต้องการแทรก. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบรายการที่ตำแหน่งที่ระบุจากคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่ต้องการลบ. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**ส่งคืน:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

บันทึกเนื้อหาของ [MathParagraph](../../com.aspose.slides/mathparagraph) นี้เป็น MathML

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |

### toLatex() {#toLatex--}
```
public final String toLatex()
```

รับสมการทางคณิตศาสตร์ในรูปแบบ LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**ส่งคืน:**
java.lang.String