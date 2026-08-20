---
title: ITextAnimationCollection
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงคอลเลกชันของแอนิเมชันข้อความ.
type: docs
url: /th/com.aspose.slides/itextanimationcollection/
---
**ส่วนติดต่อที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

แสดงคอลเลกชันของแอนิเมชันข้อความ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนองค์ประกอบตามดัชนี. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | ส่งคืนทุกองค์ประกอบ |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


ส่งคืนองค์ประกอบตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


ส่งคืนทุกองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) องค์ประกอบ. |

**ผลลัพธ์:**
com.aspose.slides.ITextAnimation[] - อาร์เรย์ของ [ITextAnimation](../../com.aspose.slides/itextanimation)