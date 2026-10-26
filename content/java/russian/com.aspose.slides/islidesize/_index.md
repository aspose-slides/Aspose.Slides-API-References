---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Представляет размер и ориентацию слайда.
type: docs
url: /ru/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Представляет размер и ориентацию слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [getSize()](#getSize--) | Получает размеры слайда в пунктах. |
| [getType()](#getType--) | Получает тип размера слайда. |
| [getOrientation()](#getOrientation--) | Получает или задаёт ориентацию слайда. |
| [setOrientation(int value)](#setOrientation-int-) | Получает или задаёт ориентацию слайда. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Устанавливает размер слайда по типу и масштабирует существующее содержимое. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Явно задаёт размеры слайда и масштабирует существующее содержимое. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Получает размеры слайда в пунктах.

--------------------

Назначение нового значения сбрасывает свойство \#getType.getType к [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) и устанавливает \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Возвращаемое значение:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```

Получает тип размера слайда.

--------------------

Назначение любого значения, отличного от [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom), корректирует \#getSize.getSize в соответствии с предопределёнными размерами, при этом сохраняет текущую ориентацию \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Возвращаемое значение:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Получает или задаёт ориентацию слайда.

--------------------

Изменение этого значения меняет местами ширину и высоту слайда.

**Возвращаемое значение:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

Получает или задаёт ориентацию слайда.

--------------------

Изменение этого значения меняет местами ширину и высоту слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

Устанавливает размер слайда по типу и масштабирует существующее содержимое.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Предопределённый размер слайда, который следует применить. |
| scaleType | int | Режим масштабирования содержимого. |

--------------------

Назначение любого значения, отличного от [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom), корректирует \#getSize.getSize на основе выбранного типа, при этом сохраняет ориентацию \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

Явно задаёт размеры слайда и масштабирует существующее содержимое.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Новая ширина слайда в пунктах. |
| height | float | Новая высота слайда в пунктах. |
| scaleType | int | Режим масштабирования содержимого. |

--------------------

Это сбрасывает свойство \#getType.getType к [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) и устанавливает \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |