---
title: ISmartArt
second_title: Справочник API Aspose.Slides для Java
description: Представляет диаграмму SmartArt.
type: docs
url: /ru/com.aspose.slides/ismartart/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Представляет диаграмму SmartArt.
## Методы

| Метод | Описание |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Возвращает коллекцию всех узлов в объекте SmartArt. |
| [getNodes()](#getNodes--) | Возвращает коллекцию корневых узлов в объекте SmartArt. |
| [getLayout()](#getLayout--) | Возвращает или задает макет объекта SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Возвращает или задает макет объекта SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Возвращает или задает быстрый стиль объекта SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Возвращает или задает быстрый стиль объекта SmartArt. |
| [getColorStyle()](#getColorStyle--) | Возвращает или задает цветовой стиль объекта SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Возвращает или задает цветовой стиль объекта SmartArt. |
| [isReversed()](#isReversed--) | Возвращает или задает состояние диаграммы SmartArt относительно направления слева направо (LTR) или справа налево (RTL), если диаграмма поддерживает обратное отображение. |
| [setReversed(boolean value)](#setReversed-boolean-) | Возвращает или задает состояние диаграммы SmartArt относительно направления слева направо (LTR) или справа налево (RTL), если диаграмма поддерживает обратное отображение. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Возвращает коллекцию всех узлов в объекте SmartArt. Только для чтения [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Возвращаемое значение:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Возвращает коллекцию корневых узлов в объекте SmartArt. Только для чтения [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Возвращаемое значение:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Возвращает или задает макет объекта SmartArt. Чтение/запись [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Возвращаемое значение:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Возвращает или задает макет объекта SmartArt. Чтение/запись [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Возвращает или задает быстрый стиль объекта SmartArt. Чтение/запись [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Возвращаемое значение:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Возвращает или задает быстрый стиль объекта SmartArt. Чтение/запись [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Возвращает или задает цветовой стиль объекта SmartArt. Чтение/запись [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Возвращаемое значение:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Возвращает или задает цветовой стиль объекта SmartArt. Чтение/запись [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Возвращает или задает состояние диаграммы SmartArt относительно направления слева направо (LTR) или справа налево (RTL), если диаграмма поддерживает обратное отображение. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Возвращает или задает состояние диаграммы SmartArt относительно направления слева направо (LTR) или справа налево (RTL), если диаграмма поддерживает обратное отображение. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |