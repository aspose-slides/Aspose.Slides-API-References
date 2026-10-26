---
title: IMathElementCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันขององค์ประกอบคณิตศาสตร์ MathElement.
type: docs
url: /th/com.aspose.slides/imathelementcollection/
---
**ส่วนติดต่อที่ทำการใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

แสดงถึงคอลเลกชันขององค์ประกอบคณิตศาสตร์ (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ. |
| [getCount()](#getCount--) | ดึงจำนวนอิลิเมนต์ที่จริง ๆ อยู่ในคอลเลกชัน. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | เพิ่มองค์ประกอบคณิตศาสตร์ที่ส่วนท้ายของคอลเลกชัน. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | กำหนดดัชนีขององค์ประกอบคณิตศาสตร์เฉพาะในคอลเลกชัน. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | แทรกองค์ประกอบคณิตศาสตร์เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบอิลิเมนต์ทั้งหมดออกจากคอลเลกชัน. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | ลบการเกิดครั้งแรกของอ็อบเจ็กต์ที่ระบุออกจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบอิลิเมนต์ที่ตำแหน่งที่ระบุในคอลเลกชัน. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | คัดลอกไปยังอาร์เรย์ที่ระบุ. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของรายการที่จะดึง |

**ส่งกลับ:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


ดึงจำนวนอิลิเมนต์ที่จริง ๆ อยู่ในคอลเลกชัน. อ่านอย่างเดียว int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**ส่งกลับ:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


เพิ่มองค์ประกอบคณิตศาสตร์ที่ส่วนท้ายของคอลเลกชัน.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement ที่จะถูกเพิ่มไปที่ส่วนท้ายของคอลเลกชัน. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


กำหนดดัชนีขององค์ประกอบคณิตศาสตร์เฉพาะในคอลเลกชัน.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์ที่ต้องการค้นหาในคอลเลกชัน. |

**ส่งกลับ:**
int - ดัชนีของรายการหากพบในคอลเลกชัน; หากไม่พบ, จะเป็น -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


แทรกองค์ประกอบคณิตศาสตร์เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ IMathElement ควรจะแทรก. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement ที่จะต้องแทรก. |

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


ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | อ็อบเจ็กต์ที่ต้องการค้นหาในคอลเลกชัน. |

**ส่งกลับ:**
boolean - true หากพบรายการในคอลเลกชัน; หากไม่, false.
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | อ็อบเจ็กต์ที่ต้องการลบจากคอลเลกชัน. |

**ส่งกลับ:**
boolean - true หากรายการถูกลบออกจากคอลเลกชันสำเร็จ; หากไม่, false. เมธอดนี้ยังคืนค่า false หากไม่พบรายการในคอลเลกชันเดิม.
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของอิลิเมนต์ที่ต้องการลบ. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


คัดลอกไปยังอาร์เรย์ที่ระบุ.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | อาร์เรย์ที่จะคัดลอกไป. |
| arrayIndex | int | ดัชนีที่เริ่มคัดลอก. |