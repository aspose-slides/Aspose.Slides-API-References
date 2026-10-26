---
title: ShapeThumbnailBounds
second_title: Aspose.Slides for Java API 參考
description: 形狀縮圖邊界類型的列舉。
type: docs
url: /zh-hant/com.aspose.slides/shapethumbnailbounds/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

形狀縮圖邊界類型的列舉。
## 欄位

| 欄位 | 描述 |
| --- | --- |
| [Slide](#Slide) | 形狀縮圖的尺寸將等於投影片尺寸。 |
| [Shape](#Shape) | 形狀縮圖的尺寸將等於形狀邊界矩形，且會考慮形狀輪廓設定。 |
| [Appearance](#Appearance) | 形狀縮圖的尺寸將等於形狀外觀（在投影片範圍內）。 |
### Slide {#Slide}
```
public static final int Slide
```

形狀縮圖的尺寸將等於投影片尺寸。形狀位置將被保存。

### Shape {#Shape}
```
public static final int Shape
```

形狀縮圖的尺寸將等於形狀邊界矩形，且會考慮形狀輪廓設定。

### Appearance {#Appearance}
```
public static final int Appearance
```

形狀縮圖的尺寸將等於形狀外觀（在投影片範圍內）。有時形狀外觀可能不適合形狀邊界。例如：旋轉、銳角的斜接、3D 效果等。