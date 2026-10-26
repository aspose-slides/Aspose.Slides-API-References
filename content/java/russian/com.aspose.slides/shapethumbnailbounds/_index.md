---
title: ShapeThumbnailBounds
second_title: Справочник API Aspose.Slides для Java
description: Перечисление типов границ миниатюры фигуры.
type: docs
url: /ru/com.aspose.slides/shapethumbnailbounds/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Перечисление типов границ миниатюры фигуры.
## Поля

| Поле | Описание |
| --- | --- |
| [Slide](#Slide) | Миниатюра фигуры будет иметь размер, равный размеру слайда. |
| [Shape](#Shape) | Миниатюра фигуры будет иметь размер, равный прямоугольнику границ фигуры с учётом настроек контура фигуры. |
| [Appearance](#Appearance) | Миниатюра фигуры будет иметь размер, равный внешнему виду фигуры (в пределах слайда). |
### Слайд {#Slide}
```
public static final int Slide
```


Миниатюра фигуры будет иметь размер, равный размеру слайда. Позиция фигуры будет сохранена.

### Фигура {#Shape}
```
public static final int Shape
```


Миниатюра фигуры будет иметь размер, равный прямоугольнику границ фигуры с учётом настроек контура фигуры.

### Внешний вид {#Appearance}
```
public static final int Appearance
```


Миниатюра фигуры будет иметь размер, равный внешнему виду фигуры (в пределах слайда). Возможны случаи, когда внешний вид фигуры не помещается в границы фигуры. Например, вращение, соединение в виде среза острого угла, 3D-эффекты и т.д.