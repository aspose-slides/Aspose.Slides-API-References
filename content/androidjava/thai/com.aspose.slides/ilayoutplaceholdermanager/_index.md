---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงผู้จัดการที่อนุญาตให้คุณเพิ่ม placeholders ไปยังสไลด์เค้าโครง
type: docs
url: /th/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

แสดงถึงผู้จัดการที่อนุญาตให้คุณเพิ่ม placeholders ไปยังสไลด์เค้าโครง

## เมธอด

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ ในแนวตั้ง |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความ |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความ ในแนวตั้ง |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บรูปภาพ |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภูมิ |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บตาราง |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภาพ SmartArt |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บวัตถุสื่อ |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บภาพออนไลน์ |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Content

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ ในแนวตั้ง

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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Content (Vertical)

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความ

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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Text

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความ ในแนวตั้ง

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Text (Vertical)

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บรูปภาพ

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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Picture

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภูมิ

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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Chart

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บตาราง

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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Table

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บแผนภาพ SmartArt

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปร่าง placeholder แบบ SmartArt ไปยังสไลด์เค้าโครง.
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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท SmartArt

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บวัตถุสื่อ

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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Media

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่าง placeholder ใหม่ลงในสไลด์เค้าโครงเพื่อเก็บภาพออนไลน์

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มรูปร่าง placeholder แบบ Online Image ไปยังสไลด์เค้าโครง.
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
| x | float | พิกัด X ของรูปร่าง placeholder ใหม่ |
| y | float | พิกัด Y ของรูปร่าง placeholder ใหม่ |
| width | float | ความกว้างของรูปร่าง placeholder ใหม่ |
| height | float | ความสูงของรูปร่าง placeholder ใหม่ |

**ผลลัพธ์:**
[IAutoShape](../../com.aspose.slides/iautoshape) - สร้าง [IAutoShape](../../com.aspose.slides/iautoshape) ด้วย placeholder ประเภท Online Image