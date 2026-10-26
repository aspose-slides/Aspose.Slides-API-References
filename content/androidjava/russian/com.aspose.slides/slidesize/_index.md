---
title: SlideSize
second_title: Aspose.Slides для Android через Java API справочник
description: Представляет размер и ориентацию слайда.
type: docs
url: /ru/com.aspose.slides/slidesize/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)  
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Представляет размер и ориентацию слайда.

## Методы

| Метод | Описание |
| --- | --- |
| [getSize()](#getSize--) | Получает размеры слайда в пунктах. |
| [getType()](#getType--) | Получает тип размера слайда. |
| [getOrientation()](#getOrientation--) | Получает или задает ориентацию слайда. |
| [setOrientation(int value)](#setOrientation-int-) | Получает или задает ориентацию слайда. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Устанавливает размер слайда по типу и масштабирует существующее содержание. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Устанавливает размеры слайда явно и масштабирует существующее содержание. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```

Получает размеры слайда в пунктах.

--------------------

Присвоение нового значения сбрасывает свойство \#getType.getType до [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) и задает \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Возвращаемое значение:**  
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```

Получает тип размера слайда.

--------------------

Присвоение любого значения, отличного от [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom), корректирует \#getSize.getSize согласно предопределённым размерам, сохраняя текущий \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

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

Устанавливает размер слайда по типу и масштабирует существующее содержание.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Предустановленный размер слайда, который следует применить. |
| scaleType | int | Режим масштабирования содержимого. |

--------------------

Присвоение любого значения, отличного от [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom), корректирует \#getSize.getSize на основе выбранного типа, сохраняя \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Устанавливает размеры слайда явно и масштабирует существующее содержание.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Новая ширина слайда в пунктах. |
| height | float | Новая высота слайда в пунктах. |
| scaleType | int | Режим масштабирования содержимого. |

--------------------

Это сбрасывает свойство \#getType.getType до [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) и задает \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).