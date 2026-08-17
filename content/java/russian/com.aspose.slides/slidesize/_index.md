---
title: SlideSize
second_title: Справочник API Aspose.Slides для Java
description: Представляет размер и ориентацию слайда.
type: docs
url: /ru/com.aspose.slides/slidesize/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Представляет размер и ориентацию слайда.
## Методы

| Method | Описание |
| --- | --- |
| [getSize()](#getSize--) | Получает размеры слайда в пунктах. |
| [getType()](#getType--) | Получает тип размера слайда. |
| [getOrientation()](#getOrientation--) | Получает или задает ориентацию слайда. |
| [setOrientation(int value)](#setOrientation-int-) | Получает или задает ориентацию слайда. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Устанавливает размер слайда по типу и масштабирует существующее содержимое. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Явно задает размеры слайда и масштабирует существующее содержимое. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


Получает размеры слайда в пунктах.

--------------------

Назначение нового значения сбрасывает свойство #getType.getType к [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) и устанавливает #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

**Возвращаемое значение:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```


Получает тип размера слайда.

--------------------

Назначение любого значения, отличного от [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom), корректирует #getSize.getSize в соответствии с предустановленными размерами, сохраняя текущие #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

**Возвращаемое значение:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Получает или задает ориентацию слайда.

--------------------

Изменение этого значения меняет местами ширину и высоту слайда.

**Возвращаемое значение:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Получает или задает ориентацию слайда.

--------------------

Изменение этого значения меняет местами ширину и высоту слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Устанавливает размер слайда по типу и масштабирует существующее содержимое.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Предустановленный размер слайда, который следует применить. |
| scaleType | int | Режим масштабирования содержимого, который следует использовать.

--------------------

Назначение любого значения, отличного от [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom), корректирует #getSize.getSize на основе выбранного типа, сохраняет #getOrientation.getOrientation/#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Устанавливает размеры слайда явно и масштабирует существующее содержимое.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Новая ширина слайда в пунктах. |
| height | float | Новая высота слайда в пунктах. |
| scaleType | int | Режим масштабирования содержимого, который следует использовать.

--------------------

Это сбрасывает свойство #getType.getType к [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) и устанавливает #getOrientation.getOrientation/#setOrientation(int).setOrientation(int). |