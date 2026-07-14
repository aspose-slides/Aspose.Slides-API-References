---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงคุณสมบัติวิวสไลด์ทั่วไป
type: docs
url: /th/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

แสดงคุณสมบัติวิวสไลด์ทั่วไป.
## เมธอด

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์ |
| [setScale(int value)](#setScale-int-) | ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์ |
| [getVariableScale()](#getVariableScale--) | ระบุว่าความเนื้อหาของมุมมองควรขยายอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบัน |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | ระบุว่าความเนื้อหาของมุมมองควรขยายอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบัน |
| [getDrawingGuides()](#getDrawingGuides--) | ส่งคืนคอลเลกชันของไกด์การวาด |

### getScale() {#getScale--}
```
public abstract int getScale()
```

ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์ อ่าน/เขียน int.

**ผลลัพธ์:**
int

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์ อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

ระบุว่าความเนื้อหาของมุมมองควรขยายอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบัน อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

ระบุว่าความเนื้อหาของมุมมองควรขยายอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบัน อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

ส่งคืนคอลเลกชันของไกด์การวาด อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // เพิ่มไกด์การวาดแนวตั้งใหม่ที่ด้านขวาของศูนย์กลางสไลด์
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // เพิ่มไกด์การวาดแนวนอนใหม่ที่ด้านล่างของศูนย์กลางสไลด์
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ผลลัพธ์:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)