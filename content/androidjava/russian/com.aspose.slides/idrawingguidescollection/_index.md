---
title: IDrawingGuidesCollection
second_title: Aspose.Slides для Android через справку Java API
description: Представляет коллекцию регулируемых руководств черчения.
type: docs
url: /ru/com.aspose.slides/idrawingguidescollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Представляет коллекцию регулируемых руководств черчения.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает руководство черчения по индексу. |
| [add(byte orientation, float position)](#add-byte-float-) | Добавляет руководство черчения в конец коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет руководство черчения по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [getCount()](#getCount--) | Получает количество всех элементов в коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Возвращает руководство черчения по индексу. Только для чтения [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возврат:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Добавляет руководство черчения в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| orientation | byte | Ориентация руководства черчения. |
| position | float | Позиция руководства черчения в пунктах. |

**Возврат:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет руководство черчения по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс руководства черчения, которое должно быть удалено. |

### clear() {#clear--}
```
public abstract void clear()
```


Удаляет все элементы из коллекции.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Получает количество всех элементов в коллекции. Только для чтения int.

**Возврат:**
int