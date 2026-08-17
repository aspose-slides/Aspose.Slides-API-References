---
title: IDrawingGuidesCollection
second_title: Aspose.Slides для Java - справочник API
description: Представляет коллекцию регулируемых направляющих рисования.
type: docs
url: /ru/com.aspose.slides/idrawingguidescollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Представляет коллекцию регулируемых направляющих рисования.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает направляющую рисования по индексу. |
| [add(byte orientation, float position)](#add-byte-float-) | Добавляет направляющую рисования в конец коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет направляющую рисования по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [getCount()](#getCount--) | Получает количество всех элементов в коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Возвращает направляющую рисования по индексу. Только для чтения [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

Добавляет направляющую рисования в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| orientation | byte | Ориентация направляющей рисования. |
| position | float | Позиция направляющей рисования в пунктах. |

**Возвращаемое значение:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет направляющую рисования по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс направляющей рисования, которую следует удалить. |

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

**Возвращаемое значение:**
int