---
title: ICellCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию ячеек.
type: docs
url: /ru/com.aspose.slides/icellcollection/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Представляет коллекцию ячеек.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает ячейку по её позиции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Возвращает ячейку по её позиции. Только для чтения [ICell](../../com.aspose.slides/icell).

--------------------

Один объект CellEx может быть возвращён для нескольких индексов в случае, когда ячейка объединена.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ICell](../../com.aspose.slides/icell)