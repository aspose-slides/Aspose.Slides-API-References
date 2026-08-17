---
title: ShapeThumbnailBounds
second_title: Aspose.Slides for Java API リファレンス
description: シェイプ サムネイル境界のタイプの列挙。
type: docs
url: /ja/com.aspose.slides/shapethumbnailbounds/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

シェイプ サムネイル境界のタイプの列挙。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Slide](#Slide) | Shape thumbnail will have the size equal to slide size. |
| [Shape](#Shape) | Shape thumbnail will have size equal to the shape bounds rectangle with taking into account shape outline settings. |
| [Appearance](#Appearance) | Shape thumbnail will have size equal to the shape appearance (in bounds of a slide). |
### スライド {#Slide}
```
public static final int Slide
```


Shape thumbnail will have the size equal to slide size. Shape position will be saved.

### 形状 {#Shape}
```
public static final int Shape
```


Shape thumbnail will have size equal to the shape bounds rectangle with taking into account shape outline settings.

### 外観 {#Appearance}
```
public static final int Appearance
```


Shape thumbnail will have size equal to the shape appearance (in bounds of a slide). It can be cases when shape appearance doesn't fit into the shape bounds. E.g. rotation, miter join of acute angle , 3D effects, etc.