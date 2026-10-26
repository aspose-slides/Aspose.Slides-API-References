---
title: MathBlock
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มบนบรรทัดของมันเอง.
type: docs
url: /th/com.aspose.slides/mathblock/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

กำหนดอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นบนบรรทัดของตัวเอง ทุกโซนคณิตศาสตร์ รวมถึงสมการ นิพจน์ อาเรย์ของสมการหรือ นิพจน์ และสูตร แสดงโดยบล็อกคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## คอนสตรัคเตอร์

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathBlock()](#MathBlock--) | สร้างอินสแตนซ์ใหม่ของคลาส MathBlock |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | รับจำนวนของ child math elements ที่จริง ๆ อยู่ในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับหรือกำหนด IMathElement ที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | รับหรือกำหนด IMathElement ที่ตำแหน่งที่ระบุ |
| [isReadOnly()](#isReadOnly--) | คืนค่า false เนื่องจากคอลเลกชันของ child elements สามารถแก้ไขได้ |
| [getChildren()](#getChildren--) | รับ child elements |
| [getParent_Immediate()](#getParent-Immediate--) | คืนค่าอ็อบเจกต์ Parent_Immediate |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | เพิ่ม MathElement ไปที่ท้ายคอลเลกชัน |
| [clear()](#clear--) | ลบทุกองค์ประกอบออกจากคอลเลกชัน |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่ |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | คัดลอกไปยังอาเรย์ที่ระบุ |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | ลบการเกิดขึ้นครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน |
| [iterator()](#iterator--) | คืน enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | ตรวจสอบตำแหน่งของ MathElement ที่ระบุในคอลเลกชัน |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | แทรก MathElement ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุจากคอลเลกชัน |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | เชื่อมต่อองค์ประกอบคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้ |
| [join(String mathText)](#join-java.lang.String-) | เชื่อมต่อข้อความคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้ |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | เชื่อมต่อบล็อกคณิตศาสตร์อื่นกับบล็อกนี้ |
| [delimit(char separatorCharacter)](#delimit-char-) | คั่น child elements ด้วยอักขระตัวคั่น (โดยไม่มีวงเล็บ) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | ใส่ child elements ของบล็อกนี้ในอักขระที่ระบุ เช่น วงเล็บ หรืออักขระอื่นเป็นกรอบ |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | ใส่ child elements ของบล็อกนี้ในอักขระที่ระบุ เช่น วงเล็บ หรืออักขระอื่นเป็นกรอบและคั่นด้วยอักขระตัวคั่น |
| [toMathArray()](#toMathArray--) | ใส่ child elements ในอาเรย์แนวตั้ง |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | บันทึกเนื้อหาของ [MathBlock](../../com.aspose.slides/mathblock) นี้เป็น MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

สร้างอินสแตนซ์ใหม่ของคลาส MathBlock

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะใส่ลงในบล็อก |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | องค์ประกอบคณิตศาสตร์ที่จะใส่ลงในบล็อก |

### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนของ child math elements ที่จริง ๆ อยู่ในคอลเลกชัน อ่านอย่างเดียว int

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**ผลลัพธ์:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

รับหรือกำหนด IMathElement ที่ตำแหน่งที่ระบุ

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของรายการ |

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement) - องค์ประกอบคณิตศาสตร์
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

รับหรือกำหนด IMMathElement ที่ตำแหน่งที่ระบุ

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของรายการ |
| value | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

คืนค่า false เนื่องจากคอลเลกชันของ child elements สามารถแก้ไขได้

**ผลลัพธ์:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับ child elements

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจกต์ Parent_Immediate อ่านอย่างเดียว IDOMObject

**ผลลัพธ์:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

เพิ่ม MathElement ไปที่ท้ายของคอลเลกชัน

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement ที่จะเพิ่มไปที่ท้ายของคอลเลกชัน |

### clear() {#clear--}
```
public final void clear()
```

ลบทุกองค์ประกอบออกจากคอลเลกชัน

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | อ็อบเจกต์ที่จะค้นหาในคอลเลกชัน |

**ผลลัพธ์:**
boolean - true หากพบ item ในคอลเลกชัน; หากไม่พบ false
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

คัดลอกไปยังอาเรย์ที่ระบุ

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | อาเรย์ที่จะคัดลอกไป |
| arrayIndex | int | ดัชนีเริ่มคัดลอก |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

ลบการเกิดขึ้นครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | อ็อบเจกต์ที่จะลบจากคอลเลกชัน |

**ผลลัพธ์:**
boolean - true หากลบ item สำเร็จจากคอลเลกชัน; หากไม่พบ false (เมธอดนี้ยังคืน false หากไม่พบ item ในคอลเลกชันเดิม)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

คืน enumerator ที่วนผ่านคอลเลกชัน

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - IGenericEnumerator ที่ใช้วนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด

**ผลลัพธ์:**
com.aspose.ms.System.Collections.IEnumerator - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

ตรวจสอบตำแหน่งของ MathElement ที่ระบุในคอลเลกชัน

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่จะค้นหาในคอลเลกชัน |

**ผลลัพธ์:**
int - ดัชนีของ item หากพบในคอลเลกชัน; หากไม่พบ -1
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

แทรก MathElement ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ต้องการแทรก MathElement |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement ที่จะแทรก |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุจากคอลเลกชัน

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ขององค์ประกอบที่จะลบ |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

เชื่อมต่อองค์ประกอบคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่ต้องการเชื่อมต่อ |

**ผลลัพธ์:**
[IMathBlock](../../com.aspose.slides/imathblock) - อินสแตนซ์ปัจจุบันของ IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

เชื่อมต่อข้อความคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ข้อความคณิตศาสตร์ที่จะเชื่อมต่อ |

**ผลลัพธ์:**
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock ใหม่ที่มีอินสแตนซ์นี้และอากิวเมนต์ที่ระบุ
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

เชื่อมต่อบล็อกคณิตศาสตร์อื่นกับบล็อกนี้

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกที่ต้องการเชื่อมต่อ |

**ผลลัพธ์:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกคณิตศาสตร์นี้หลังการเชื่อมต่อ
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

คั่น child elements ด้วยอักขระตัวคั่น (โดยไม่มีวงเล็บ)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| separatorCharacter | char | อักขระตัวคั่น |

**ผลลัพธ์:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

ใส่ child elements ของบล็อกนี้ในอักขระที่ระบุ เช่น วงเล็บ หรืออักขระอื่นเป็นกรอบ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char | อักขระเริ่มต้น (ส่วนใหญ่คือวงเล็บซ้าย) |
| endingCharacter | char | อักขระสิ้นสุด (ส่วนใหญ่คือวงเล็บขวา) |

**ผลลัพธ์:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter) ที่รวมอักขระที่ระบุเป็นกรอบ
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

ใส่ child elements ของบล็อกนี้ในอักขระที่ระบุ เช่น วงเล็บ หรืออักขระอื่นเป็นกรอบและคั่นด้วยอักขระตัวคั่น

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char | อักขระเริ่มต้น (ส่วนใหญ่คือวงเล็บซ้าย) |
| endingCharacter | char | อักขระสิ้นสุด (ส่วนใหญ่คือวงเล็บขวา) |
| separatorCharacter | char | อักขระตัวคั่น |

**ผลลัพธ์:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter) ที่รวมอักขระที่ระบุเป็นกรอบและตัวคั่น
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

ใส่ child elements ในอาเรย์แนวตั้ง

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**ผลลัพธ์:**
[IMathArray](../../com.aspose.slides/imatharray) - อินสแตนซ์ใหม่ของประเภท [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

บันทึกเนื้อหาของ [MathBlock](../../com.aspose.slides/mathblock) นี้เป็น MathML

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |