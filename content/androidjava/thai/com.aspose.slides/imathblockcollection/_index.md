---
title: IMathBlockCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คอลเลกชันของบล็อกคณิตศาสตร์ IMathBlock
type: docs
url: /th/com.aspose.slides/imathblockcollection/
---
**ส่วนต่อประสานที่นำมาใช้ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

คอลเลกชันของบล็อกคณิตศาสตร์ (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | เพิ่ม IMMathBlock ไปยังท้ายคอลเลกชัน |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | แทรก IMMathBlock เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบรายการที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่ |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | กำหนดตำแหน่งของ IMMathBlock ที่ระบุในคอลเลกชัน |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริง |
| [get_Item(int index)](#get-Item-int-) | รับรายการที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | รับรายการที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบองค์ประกอบทั้งหมดจากคอลเลกชัน |
### add(IMMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

เพิ่ม IMMathBlock ไปยังท้ายของคอลเลกชัน

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**พารามิ터:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกคณิตศาสตร์ที่จะถูกเพิ่มไปยังท้ายของคอลเลกชัน |

### insert(int index, IMMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

แทรก IMMathBlock เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ต้องการแทรกรายการ |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMMathBlock ที่จะทำการแทรก |

### remove(IMMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | อ็อบเจ็กต์ที่จะลบออกจากคอลเลกชัน |

**ผลลัพธ์:**
boolean - true หากรายการถูกลบออกจากคอลเลกชันสำเร็จ; มิฉะนั้น false. เมธอดนี้ยังคืนค่า false หากไม่พบรายการในคอลเลกชันต้นฉบับ
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบรายการที่ตำแหน่งที่ระบุในคอลเลกชัน

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่จะลบ |

### contains(IMMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | อ็อบเจ็กต์ที่จะค้นหาในคอลเลกชัน |

**ผลลัพธ์:**
boolean - true หากรายการพบในคอลเลกชัน; มิฉะนั้น false.
### indexOf(IMMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

กำหนดตำแหน่งของ IMMathBlock ที่ระบุในคอลเลกชัน

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | รายการที่จะค้นหาในคอลเลกชัน |

**ผลลัพธ์:**
int - ดัชนีของรายการหากพบในคอลเลกชัน; มิฉะนั้น -1
### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริง. อ่านอย่างเดียว int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**ผลลัพธ์:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

รับรายการที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่จะรับ |

**ผลลัพธ์:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกของข้อความคณิตศาสตร์
### set_Item(int index, IMMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

รับรายการที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่จะตั้งค่า |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกของข้อความคณิตศาสตร์

### clear() {#clear--}
```
public abstract void clear()
```

ลบองค์ประกอบทั้งหมดจากคอลเลกชัน

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```