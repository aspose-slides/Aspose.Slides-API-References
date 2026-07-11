---
title: IVbaModuleCollection
second_title: Aspose.Slides для Android через Java API
description: Представляет коллекцию модулей проекта VBA.
type: docs
url: /ru/com.aspose.slides/ivbamodulecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Представляет коллекцию модулей проекта VBA.

## Методы

| Method | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Добавляет новый пустой модуль в проект VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Удаляет первое вхождение указанного объекта из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

Добавляет новый пустой модуль в проект VBA.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя модуля |

**Возвращаемое значение:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Добавленный модуль.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

Удаляет первое вхождение указанного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Модуль, который нужно удалить из коллекции. |