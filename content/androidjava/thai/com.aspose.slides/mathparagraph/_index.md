---
title: MathParagraph
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ย่อหน้าทางคณิตศาสตร์ที่เป็นคอนเทนเนอร์สำหรับบล็อกทางคณิตศาสตร์ IMathBlock
type: docs
url: /th/com.aspose.slides/mathparagraph/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
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
## Constructors

| Constructor | Description |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathParagraph |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathParagraph |
## Methods

| Method | Description |
| --- | --- |
| [getJustification()](#getJustification--) | การจัดแนวย่อหน้า ค่าเริ่มต้น: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | การจัดแนวย่อหน้า ค่าเริ่มต้น: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | คืนค่าอ็อบเจกต์ Parent_Immediate |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริง |
| [get_Item(int index)](#get-Item-int-) | รับรายการที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | รับรายการที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบองค์ประกอบทั้งหมดออกจากคอลเลกชัน |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | เพิ่ม IMathBlock ไปยังท้ายของคอลเลกชัน |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุออกจากคอลเลกชัน |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่ |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | ตรวจสอบดัชนีของ IMathBlock ที่ระบุในคอลเลกชัน |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | แทรก IMathBlock ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบรายการที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | บันทึกเนื้อหาของ [MathParagraph](../../com.aspose.slides/mathparagraph) นี้เป็น MathML |
| [toLatex()](#toLatex--) | รับสมการทางคณิตย์ศาสตร์ในรูปแบบ LaTeX |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```


เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathParagraph

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


เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathParagraph

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```


การจัดแนวย่อหน้า ค่าเริ่มต้น: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Returns:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```


การจัดแนวย่อหน้า ค่าเริ่มต้น: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


คืนค่าอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```


รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริง. อ่านอย่างเดียว int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```


รับรายการที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMathBlock](../../com.aspose.slides/imathblock).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่ต้องการรับ |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกของข้อความทางคณิตศาสตร์
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```


รับรายการที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMathBlock](../../com.aspose.slides/imathblock).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่ต้องการรับ |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกของข้อความทางคณิตศาสตร์ |

### clear() {#clear--}
```
public final void clear()
```


ลบองค์ประกอบทั้งหมดออกจากคอลเลกชัน

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


เพิ่ม IMathBlock ไปยังท้ายของคอลเลกชัน

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกทางคณิตศาสตร์ที่จะถูกเพิ่มไปยังท้ายของคอลเลกชัน |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```


ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุออกจากคอลเลกชัน

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | อ็อบเจกต์ที่ต้องการลบจากคอลเลกชัน |

**Returns:**
boolean - true หาก mathBlock ถูกลบออกจากคอลเลกชันสำเร็จ; มิฉะนั้น false. วิธีนี้จะคืนค่า false หาก mathBlock ไม่พบในคอลเลกชันต้นทาง
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```


ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | อ็อบเจกต์ที่ต้องการค้นหาในคอลเลกชัน |

**Returns:**
boolean - true หาก mathBlock พบในคอลเลกชัน; มิฉะนั้น false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```


ตรวจสอบดัชนีของ IMathBlock ที่ระบุในคอลเลกชัน

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | รายการที่ต้องการค้นหาในคอลเลกชัน |

**Returns:**
int - ดัชนีของ mathBlock หากพบในคอลเลกชัน; มิฉะนั้น -1
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```


แทรก IMathBlock ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ต้องการแทรกรายการ |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock ที่ต้องการแทรก |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบรายการที่ตำแหน่งที่ระบุในคอลเลกชัน

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่ต้องการลบ |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```




**Returns:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


บันทึกเนื้อหาของ [MathParagraph](../../com.aspose.slides/mathparagraph) นี้เป็น MathML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |

### toLatex() {#toLatex--}
```
public final String toLatex()
```


รับสมการทางคณิตย์ศาสตร์ในรูปแบบ LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Returns:**
java.lang.String