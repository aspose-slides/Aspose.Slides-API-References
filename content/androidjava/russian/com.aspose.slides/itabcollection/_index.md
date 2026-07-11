---
title: ITabCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию Tab.
type: docs
url: /ru/com.aspose.slides/itabcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Представляет коллекцию Tab.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [add(double position, int align)](#add-double-int-) | Добавляет Tab в коллекцию. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Добавляет Tab в коллекцию. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [ITab](../../com.aspose.slides/itab).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Добавляет Tab в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | double | Позиция Tab. |
| align | int | Выравнивание Tab. |

**Возвращаемое значение:**
[ITab](../../com.aspose.slides/itab) - Добавленный Tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Добавляет Tab в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Объект Tab, который будет добавлен в конец коллекции. |

**Возвращаемое значение:**
int - Индекс, по которому был добавлен таб.
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы из коллекции.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |