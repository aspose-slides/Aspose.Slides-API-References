---
title: ShapeThumbnailBounds
second_title: Aspose.Slides for Android via Java API 參考文件
description: 列舉形狀縮圖邊界的類型。
type: docs
url: /zh-hant/com.aspose.slides/shapethumbnailbounds/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

列舉形狀縮圖邊界的類型。
## 欄位

| Field | Description |
| --- | --- |
| [Slide](#Slide) | 形狀縮圖的大小將等於投影片大小。 |
| [Shape](#Shape) | 形狀縮圖的大小將等於形狀邊界矩形，並考慮形狀輪廓設定。 |
| [Appearance](#Appearance) | 形狀縮圖的大小將等於形狀外觀（在投影片邊界內）。 |
### Slide {#Slide}
```
public static final int Slide
```

形狀縮圖的大小將等於投影片大小。形狀位置將被保存。

### Shape {#Shape}
```
public static final int Shape
```

形狀縮圖的大小將等於形狀邊界矩形，並考慮形狀輪廓設定。

### Appearance {#Appearance}
```
public static final int Appearance
```

形狀縮圖的大小將等於形狀外觀（在投影片邊界內）。在形狀外觀不符合形狀邊界的情況下也可能發生。例如旋轉、銳角的斜接、3D 效果等。