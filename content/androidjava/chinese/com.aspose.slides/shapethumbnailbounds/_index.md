---
title: ShapeThumbnailBounds
second_title: Aspose.Slides for Android via Java API 参考
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
| [Slide](#Slide) | Shape 缩略图的大小将等于 Slide 大小。 |
| [Shape](#Shape) | Shape 缩略图的大小将等于 shape 边界矩形，并考虑 shape 轮廓设置。 |
| [Appearance](#Appearance) | Shape 缩略图的大小将等于 shape 外观（在 Slide 边界内）。 |
### 幻灯片 {#Slide}
```
public static final int Slide
```

Shape 缩略图的大小将等于 Slide 大小。 Shape 位置将被保存。

### 形状 {#Shape}
```
public static final int Shape
```

Shape 缩略图的大小将等于 shape 边界矩形，并考虑 shape 轮廓设置。

### 外观 {#Appearance}
```
public static final int Appearance
```

Shape 缩略图的大小将等于 shape 外观（在 Slide 边界内）。 可能出现 shape 外观不适合 shape 边界的情况。例如，旋转、锐角的斜接、3D 效果等。