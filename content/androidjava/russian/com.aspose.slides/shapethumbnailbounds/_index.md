---
title: ShapeThumbnailBounds
second_title: Aspose.Slides для Android через справочник Java API
description: Перечисление типов ограничений миниатюры фигуры.
type: docs
url: /ru/com.aspose.slides/shapethumbnailbounds/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Перечисление типов ограничений миниатюры фигуры.
## Поля

| Field | Description |
| --- | --- |
| [Slide](#Slide) | Миниатюра фигуры будет иметь размер, равный размеру слайда. |
| [Shape](#Shape) | Миниатюра фигуры будет иметь размер, равный прямоугольнику ограничивающих границ фигуры с учётом настроек контура фигуры. |
| [Appearance](#Appearance) | Миниатюра фигуры будет иметь размер, равный внешнему виду фигуры (в границах слайда). |
### Slide {#Slide}
```
public static final int Slide
```

Миниатюра фигуры будет иметь размер, равный размеру слайда. Положение фигуры будет сохранено.

### Shape {#Shape}
```
public static final int Shape
```

Миниатюра фигуры будет иметь размер, равный прямоугольнику ограничивающих границ фигуры с учётом настроек контура фигуры.

### Appearance {#Appearance}
```
public static final int Appearance
```

Миниатюра фигуры будет иметь размер, равный внешнему виду фигуры (в границах слайда). Возможны случаи, когда внешний вид фигуры не помещается в границы фигуры. Например, вращение, срез соединения острым углом, 3D-эффекты и т.д.