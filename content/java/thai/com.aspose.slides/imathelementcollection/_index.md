---
title: IMathElementCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงคอลเลกชันของอิลิเมนต์คณิตศาสตร์ MathElement.
type: docs
url: /th/com.aspose.slides/imathelementcollection/
---
**ส่วนติดต่อที่ทำทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Represents a collection of mathematical elements (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## วิธีการ

| Method | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับอิลิเมนต์ที่ตำแหน่งที่ระบุ |
| [getCount()](#getCount--) | รับจำนวนของอิลิเมนต์ที่จริง ๆ แล้วอยู่ในคอลเลกชัน |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | เพิ่มอิลิเมนต์คณิตศาสตร์ไปที่ท้ายของคอลเลกชัน |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | กำหนดดัชนีของอิลิเมนต์คณิตศาสตร์เฉพาะในคอลเลกชัน |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | แทรกอิลิเมนต์คณิตศาสตร์เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบอิลิเมนต์ทั้งหมดออกจากคอลเลกชัน |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่ |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | ลบการเกิดครั้งแรกของอ็อบเจ็กต์ที่ระบุออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบอิลิเมนต์ที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | คัดลอกไปยังอาเรย์ที่ระบุ |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


รับอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่จะรับ |

**ค่าที่คืน:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


รับจำนวนของอิลิเมนต์ที่จริง ๆ แล้วอยู่ในคอลเลกชัน. อ่านอย่างเดียว int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**ค่าที่คืน:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


เพิ่มอิลิเมนต์คณิตศาสตร์ไปที่ท้ายของคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement ที่จะเพิ่มไปที่ท้ายของคอลเลกชัน |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


กำหนดดัชนีของอิลิเมนต์คณิตศาสตร์เฉพาะในคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์ที่ต้องการค้นหาในคอลเลกชัน |

**ค่าที่คืน:**
int - ดัชนีของ item หากพบในคอลเลกชัน; ไม่เช่นนั้นให้ -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


แทรกอิลิเมนต์คณิตศาสตร์เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ต้องการแทรก IMathElement |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement ที่จะทำการแทรก |

### clear() {#clear--}
```
public abstract void clear()
```


ลบอิลิเมนต์ทั้งหมดออกจากคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```


กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | อ็อบเจ็กต์ที่ต้องการค้นหาในคอลเลกชัน |

**ค่าที่คืน:**
boolean - true หากพบ item ในคอลเลกชัน; ไม่เช่นนั้น false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


ลบการเกิดครั้งแรกของอ็อบเจ็กต์ที่ระบุออกจากคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | อ็อบเจ็กต์ที่จะลบออกจากคอลเลกชัน |

**ค่าที่คืน:**
boolean - true หาก item ถูกลบสำเร็จ; ไม่เช่นนั้น false. วิธีการนี้ยังคืนค่า false หากไม่พบ item ในคอลเลกชันต้นฉบับ.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบอิลิเมนต์ที่ตำแหน่งที่ระบุในคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของอิลิเมนต์ที่ต้องการลบ |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


คัดลอกไปยังอาเรย์ที่ระบุ.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | อาเรย์ที่จะคัดลอกไป |
| arrayIndex | int | ดัชนีที่เริ่มคัดลอก |