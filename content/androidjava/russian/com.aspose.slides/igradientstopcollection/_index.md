---
title: IGradientStopCollection
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет коллекцию градиентных остановок.
type: docs
url: /ru/com.aspose.slides/igradientstopcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Представляет коллекцию градиентных остановок.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает градиентную остановку по индексу. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Создает новую градиентную остановку и добавляет её в конец коллекции. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [removeAt(int index)](#removeAt-int-) | Удаляет градиентную остановку по указанному индексу. |
| [clear()](#clear--) | Удаляет все градиентные остановки из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Возвращает градиентную остановку по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

Создает новую градиентную остановку и добавляет её в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | float | Позиция новой градиентной остановки. |
| color | java.lang.Integer | Цвет новой градиентной остановки. |

**Возвращаемое значение:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Индекс новой градиентной остановки в коллекции.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Создает новую градиентную остановку и добавляет её в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | float | Позиция новой градиентной остановки. |
| presetColor | int | Цвет новой градиентной остановки. |

**Возвращаемое значение:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Индекс новой градиентной остановки в коллекции.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Создает новую градиентную остановку и добавляет её в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | float | Позиция новой градиентной остановки. |
| schemeColor | int | Цвет новой градиентной остановки. |

**Возвращаемое значение:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Индекс новой градиентной остановки в коллекции.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, куда будет вставлена новая градиентная остановка. |
| position | float | Позиция новой градиентной остановки. |
| color | java.lang.Integer | Цвет новой градиентной остановки. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, куда будет вставлена новая градиентная остановка. |
| position | float | Позиция новой градиентной остановки. |
| presetColor | int | Цвет новой градиентной остановки. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Создает новую градиентную остановку и вставляет её в указанную позицию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в коллекции, куда будет вставлена новая градиентная остановка. |
| position | float | Позиция новой градиентной остановки. |
| schemeColor | int | Цвет новой градиентной остановки. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет градиентную остановку по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс градиентной остановки, которую следует удалить. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все градиентные остановки из коллекции.