---
title: LayoutPlaceholderManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นผู้จัดการที่อนุญาตให้คุณเพิ่มตัวตำแหน่งลงในสไลด์เลย์เอาต์.
type: docs
url: /th/com.aspose.slides/layoutplaceholdermanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

เป็นตัวจัดการที่อนุญาตให้คุณเพิ่มตัวตำแหน่งลงในสไลด์เลย์เอาต์
## วิธีการ

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บเนื้อหา เช่น รูปภาพ, ตาราง, สื่อ หรือข้อความ |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บเนื้อหา เช่น รูปภาพ, ตาราง, สื่อ หรือข้อความในแนวตั้ง |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บเนื้อหาข้อความ |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บเนื้อหาข้อความในแนวตั้ง |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เออต์เพื่อเก็บรูปภาพ |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บแผนภูมิ |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บตาราง |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บไดอะแกรม SmartArt |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บอ็อบเจ็กต์สื่อ |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บรูปภาพออนไลน์ |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บเนื้อหา เช่น รูปภาพ, ตาราง, สื่อ หรือข้อความ

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Content
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บเนื้อหา เช่น รูปภาพ, ตาราง, สื่อ หรือข้อความในแนวตั้ง

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง Content (Vertical) ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Content (Vertical)
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บเนื้อหาข้อความ

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง Text ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Text
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บเนื้อหาข้อความในแนวตั้ง

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง Text (Vertical) ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Text (Vertical)
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บรูปภาพ

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง Picture ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Picture
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บแผนภูมิ

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง Chart ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Chart
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บตาราง

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง Table ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Table
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บไดอะแกรม SmartArt

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง SmartArt ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง SmartArt
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บอ็อบเจ็กต์สื่อ

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง Media ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Media
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


เพิ่มรูปร่างตัวตำแหน่งใหม่ลงในสไลด์เลย์เอาต์เพื่อเก็บรูปภาพออนไลน์

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปร่างตัวตำแหน่ง Online Image ไปยังสไลด์เลย์เอาต์.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) พร้อมตัวตำแหน่ง Online Image