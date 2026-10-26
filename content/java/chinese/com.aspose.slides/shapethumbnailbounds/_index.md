---
title: ShapeThumbnailBounds
second_title: Aspose.Slides Java API 参考
description: 形状缩略图边界类型的枚举。
type: docs
url: /zh/com.aspose.slides/shapethumbnailbounds/
---
**继承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

形状缩略图边界类型的枚举。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Slide](#Slide) | 形状缩略图的大小将等于幻灯片大小。 |
| [Shape](#Shape) | 形状缩略图的大小将等于形状边界矩形的大小，并考虑形状轮廓设置。 |
| [Appearance](#Appearance) | 形状缩略图的大小将等于形状外观（在幻灯片范围内）。 |
### Slide {#Slide}
```
public static final int Slide
```

形状缩略图的大小将等于幻灯片大小。形状位置将被保存。

### Shape {#Shape}
```
public static final int Shape
```

形状缩略图的大小将等于形状边界矩形的大小，并考虑形状轮廓设置。

### Appearance {#Appearance}
```
public static final int Appearance
```

形状缩略图的大小将等于形状外观（在幻灯片范围内）。可能出现形状外观不符合形状边界的情况。例如，旋转、锐角的斜接、3D 效果等。