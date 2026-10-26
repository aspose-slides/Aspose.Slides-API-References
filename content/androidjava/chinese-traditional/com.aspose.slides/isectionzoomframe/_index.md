---
title: ISectionZoomFrame
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示投影片中的 Section Zoom 物件。
type: docs
url: /zh-hant/com.aspose.slides/isectionzoomframe/
---
**所有已實作的介面：**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

表示投影片中的 Section Zoom 物件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | 取得或設置 Section Zoom 物件所連結的節段物件。 |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | 取得或設置 Section Zoom 物件所連結的節段物件。 |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

取得或設置 Section Zoom 物件所連結的節段物件。 讀/寫 [ISection](../../com.aspose.slides/isection)。

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**回傳值：**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

取得或設置 Section Zoom 物件所連結的節段物件。 讀/寫 [ISection](../../com.aspose.slides/isection)。

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |