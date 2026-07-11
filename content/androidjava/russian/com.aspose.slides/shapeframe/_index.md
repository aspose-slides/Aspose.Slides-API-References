---
title: ShapeFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет свойства рамки фигуры.
type: docs
url: /ru/com.aspose.slides/shapeframe/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)  
```
public class ShapeFrame implements IShapeFrame
```

Представляет свойства рамки фигуры.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Создает новые свойства рамки фигуры. |

## Методы

| Метод | Описание |
| --- | --- |
| [getX()](#getX--) | Возвращает координату X верхнего левого угла рамки. |
| [getY()](#getY--) | Возвращает координату Y верхнего левого угла рамки. |
| [getWidth()](#getWidth--) | Возвращает ширину рамки. |
| [getHeight()](#getHeight--) | Возвращает высоту рамки. |
| [getRotation()](#getRotation--) | Возвращает количество градусов, на которое рамка повернута вокруг оси Z. |
| [getCenterX()](#getCenterX--) | Возвращает координату X центра рамки. |
| [getCenterY()](#getCenterY--) | Возвращает координату Y центра рамки. |
| [getFlipH()](#getFlipH--) | Определяет, перевёрнута ли рамка по горизонтали. |
| [getFlipV()](#getFlipV--) | Определяет, перевёрнута ли рамка по вертикали. |
| [getRectangle()](#getRectangle--) | Возвращает координаты рамки. |
| [deepClone()](#deepClone--) | Клонирует |
| [cloneT()](#cloneT--) | Клонирует. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному объекту. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному объекту. |

### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Создает новые свойства рамки фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X рамки. |
| y | float | Координата Y рамки. |
| width | float | Ширина рамки. |
| height | float | Высота рамки. |
| flipH | byte | True, если рамка перевёрнута по горизонтали. |
| flipV | byte | True, если рамка перевёрнута по вертикали. |
| rotationAngle | float | Количество градусов, на которое рамка повернута. |

### getX() {#getX--}
```
public final float getX()
```

Возвращает координату X верхнего левого угла рамки. Только для чтения float.

**Возвращаемое значение:**  
float

### getY() {#getY--}
```
public final float getY()
```

Возвращает координату Y верхнего левого угла рамки. Только для чтения float.

**Возвращаемое значение:**  
float

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Возвращает ширину рамки. Только для чтения float.

**Возвращаемое значение:**  
float

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Возвращает высоту рамки. Только для чтения float.

**Возвращаемое значение:**  
float

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Возвращает количество градусов, на которое рамка повернута вокруг оси Z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Только для чтения float.

**Возвращаемое значение:**  
float

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Возвращает координату X центра рамки. Только для чтения float.

**Возвращаемое значение:**  
float

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Возвращает координату Y центра рамки. Только для чтения float.

**Возвращаемое значение:**  
float

### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Определяет, перевёрнута ли рамка по горизонтали. Только для чтения [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**  
byte

### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Определяет, перевёрнута ли рамка по вертикали. Только для чтения [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**  
byte

### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Возвращает координаты рамки. Только для чтения android.graphics.RectF.

**Возвращаемое значение:**  
android.graphics.RectF

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Клонирует

**Возвращаемое значение:**  
java.lang.Object - Клонированная рамка фигуры.

### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Клонирует.

**Возвращаемое значение:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Клонированная рамка фигуры.

### hashCode() {#hashCode--}
```
public int hashCode()
```

**Возвращаемое значение:**  
int

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Возвращает значение, указывающее, равен ли этот экземпляр указанному объекту.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект, с которым сравнивается этот экземпляр. |

**Возвращаемое значение:**  
boolean - **true**, если obj является ShapeFrame, имеющим то же значение, что и этот экземпляр; иначе **false**.

### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Возвращает значение, указывающее, равен ли этот экземпляр указанному объекту.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Экземпляр ShapeFRameEx для сравнения с этим объектом. |

**Возвращаемое значение:**  
boolean - **true**, если value является ShapeFrame, имеющим то же значение, что и этот экземпляр; иначе **false**.