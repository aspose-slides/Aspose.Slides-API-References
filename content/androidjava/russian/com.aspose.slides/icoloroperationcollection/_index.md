---
title: IColorOperationCollection
second_title: Aspose.Slides для Android через Java API Справочник
description: Представляет коллекцию операций цветового преобразования.
type: docs
url: /ru/com.aspose.slides/icoloroperationcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Представляет коллекцию операций цветового преобразования.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает или задает операцию по указанному индексу. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Возвращает или задает операцию по указанному индексу. |
| [add(int operation, float parameter)](#add-int-float-) | Добавляет новую операцию в конец коллекции. |
| [add(int operation)](#add-int-) | Добавляет новую операцию в конец коллекции. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Вставляет новую операцию в коллекцию. |
| [insert(int position, int operation)](#insert-int-int-) | Вставляет новую операцию в коллекцию. |
| [removeAt(int index)](#removeAt-int-) | Удаляет цветовую операцию из коллекции. |
| [clear()](#clear--) | Удаляет все цветовые операции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Возвращает или задает операцию по указанному индексу. Чтение/запись [IColorOperation](../../com.aspose.slides/icoloroperation).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Возвращает или задает операцию по указанному индексу. Чтение/запись [IColorOperation](../../com.aspose.slides/icoloroperation).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Добавляет новую операцию в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operation | int | Тип операции. |
| parameter | float | Параметр операции. |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Добавленная операция.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Добавляет новую операцию в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operation | int | Тип операции. |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Добавленная операция.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Вставляет новую операцию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | int | Индекс, по которому будет вставлена операция. |
| operation | int | Тип операции. |
| parameter | float | Параметр операции. |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Вставленная операция.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Вставляет новую операцию в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | int | Индекс, по которому будет вставлена операция. |
| operation | int | Тип операции. |

**Возвращаемое значение:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Вставленная операция.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет цветовую операцию из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс цветовой операции для удаления. |
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все цветовые операции.