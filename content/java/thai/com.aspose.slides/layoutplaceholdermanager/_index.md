---
title: LayoutPlaceholderManager
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวจัดการที่อนุญาตให้คุณเพิ่ม placeholder ลงในสไลด์เค้าโครง
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

เป็นตัวจัดการที่ช่วยให้คุณเพิ่ม placeholder ลงในสไลด์เค้าโครง.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความในแนวตั้ง |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อความข้อความ |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อความข้อความในแนวตั้ง |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บรูปภาพ |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภูมิ |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บตาราง |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บไดอะแกรม SmartArt |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บวัตถุสื่อ |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บภาพออนไลน์ |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ

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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Content

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความในแนวตั้ง

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Content (Vertical)

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อความข้อความ

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Text

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อความข้อความในแนวตั้ง

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Text (Vertical)

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บรูปภาพ

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Picture

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภูมิ

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Chart

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บตาราง

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Table

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บไดอะแกรม SmartArt

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท SmartArt

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บวัตถุสื่อ

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Media

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปแบบ placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บภาพออนไลน์

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มรูปแบบ placeholder ของภาพออนไลน์ลงในสไลด์เค้าโครง.
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
| x | float | พิกัด X ของรูปแบบ placeholder ใหม่ |
| y | float | พิกัด Y ของรูปแบบ placeholder ใหม่ |
| width | float | ความกว้างของรูปแบบ placeholder ใหม่ |
| height | float | ความสูงของรูปแบบ placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Online Image