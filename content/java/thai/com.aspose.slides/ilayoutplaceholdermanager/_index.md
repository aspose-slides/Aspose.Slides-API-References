---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /th/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

แสดงผู้จัดการที่อนุญาตให้คุณเพิ่มตัวตำแหน่งในสไลด์เลเอาต์

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความในแนวตั้ง |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุข้อความ |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุข้อความในแนวตั้ง |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุรูปภาพ |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุแผนภูมิ |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุตาราง |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุไดอะแกรม SmartArt |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุวัตถุสื่อ |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุภาพออนไลน์ |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความ

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Content placeholder.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุเนื้อหา เช่น รูปภาพ ตาราง สื่อ หรือข้อความในแนวตั้ง

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Content (Vertical) placeholder.

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุข้อความ

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Text placeholder.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุข้อความในแนวตั้ง

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Text (Vertical) placeholder.

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุรูปภาพ

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Picture placeholder.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุแผนภูมิ

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Chart placeholder.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุตาราง

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Table placeholder.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุไดอะแกรม SmartArt

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a SmartArt placeholder.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุวัตถุสื่อ

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Media placeholder.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

เพิ่มรูปร่างตัวตำแหน่งใหม่ในสไลด์เลเอาต์เพื่อบรรจุภาพออนไลน์

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | พิกัด X ของรูปร่างตัวตำแหน่งใหม่ |
| y | float | พิกัด Y ของรูปร่างตัวตำแหน่งใหม่ |
| width | float | ความกว้างของรูปร่างตัวตำแหน่งใหม่ |
| height | float | ความสูงของรูปร่างตัวตำแหน่งใหม่ |

**ค่าที่ส่งคืน:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with an Online Image placeholder.