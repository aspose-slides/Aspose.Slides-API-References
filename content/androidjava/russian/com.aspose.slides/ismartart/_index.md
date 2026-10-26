---
title: ISmartArt
second_title: Aspose.Slides для Android через справочник Java API
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
| [getLayout()](#getLayout--) | Возвращает или задаёт макет объекта SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Возвращает или задаёт макет объекта SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Возвращает или задаёт быстрый стиль объекта SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Возвращает или задаёт быстрый стиль объекта SmartArt. |
| [getColorStyle()](#getColorStyle--) | Возвращает или задаёт цветовой стиль объекта SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Возвращает или задаёт цветовой стиль объекта SmartArt. |
| [isReversed()](#isReversed--) | Возвращает или задаёт состояние диаграммы SmartArt относительно (слева направо) LTR или (справа налево) RTL, если диаграмма поддерживает обратный порядок. |
| [setReversed(boolean value)](#setReversed-boolean-) | Возвращает или задаёт состояние диаграммы SmartArt относительно (слева направо) LTR или (справа налево) RTL, если диаграмма поддерживает обратный порядок. |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Возвращает коллекцию всех узлов в объекте SmartArt. Только для чтения [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Возврат:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Возвращает коллекцию корневых узлов в объекте SmartArt. Только для чтения [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Возврат:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Возвращает или задаёт макет объекта SmartArt. Чтение/запись [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Возврат:**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Возвращает или задаёт макет объекта SmartArt. Чтение/запись [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Возвращает или задаёт быстрый стиль объекта SmartArt. Чтение/запись [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Возврат:**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickShape(int value)
```

Возвращает или задаёт быстрый стиль объекта SmartArt. Чтение/запись [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Возвращает или задаёт цветовой стиль объекта SmartArt. Чтение/запись [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Возврат:**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Возвращает или задаёт цветовой стиль объекта SmartArt. Чтение/запись [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Возвращает или задаёт состояние диаграммы SmartArt относительно (слева направо) LTR или (справа налево) RTL, если диаграмма поддерживает обратный порядок. Чтение/запись boolean.

**Возврат:**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Возвращает или задаёт состояние диаграммы SmartArt относительно (слева направо) LTR или (справа налево) RTL, если диаграмма поддерживает обратный порядок. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |