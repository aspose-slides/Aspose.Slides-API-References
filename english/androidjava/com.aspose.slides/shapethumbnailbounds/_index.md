---
title: ShapeThumbnailBounds
second_title: Aspose.Slides for Android via Java API Reference
description:  Enumeration of types of shape thumbnail bounds.
type: docs
weight: 491
url: /androidjava/com.aspose.slides/shapethumbnailbounds/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Enumeration of types of shape thumbnail bounds.
## Fields

| Field | Description |
| --- | --- |
| [Slide](#Slide) | Shape thumbnail will have the size equal to slide size. |
| [Shape](#Shape) | Shape thumbnail will have size equal to the shape bounds rectangle with taking into account shape outline settings. |
| [Appearance](#Appearance) | Shape thumbnail will have size equal to the shape appearance (in bounds of a slide). |
### Slide {#Slide}
```
public static final int Slide
```


Shape thumbnail will have the size equal to slide size. Shape position will be saved.

### Shape {#Shape}
```
public static final int Shape
```


Shape thumbnail will have size equal to the shape bounds rectangle with taking into account shape outline settings.

### Appearance {#Appearance}
```
public static final int Appearance
```


Shape thumbnail will have size equal to the shape appearance (in bounds of a slide). It can be cases when shape appearance doesn't fit into the shape bounds. E.g. rotation, miter join of acute angle , 3D effects, etc.

