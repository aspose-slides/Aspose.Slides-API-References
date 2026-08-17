---
title: ICommentAuthorCollection
second_title: Aspose.Slides для Java API Справочник
description: Представляет коллекцию авторов комментариев.
type: docs
url: /ru/com.aspose.slides/icommentauthorcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Представляет коллекцию авторов комментариев.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Добавляет нового автора в конец коллекции. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми авторами. |
| [findByName(String name)](#findByName-java.lang.String-) | Находит автора в коллекции по имени. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Находит автора в коллекции по имени и инициалам. |
| [removeAt(int index)](#removeAt-int-) | Удаляет автора по указанному индексу в коллекции. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Удаляет первое вхождение указанного автора в коллекции. |
| [clear()](#clear--) | Удаляет всех авторов из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Получает элемент по указанному индексу. Только для чтения [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Добавляет нового автора в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя нового автора. |
| initials | java.lang.String | Инициалы нового автора. |

**Возвращаемое значение:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Новый [ICommentAuthor](../../com.aspose.slides/icommentauthor) объект.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Создаёт и возвращает массив со всеми авторами.

**Возвращаемое значение:**
com.aspose.slides.ICommentAuthor[] - Массив [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Находит автора в коллекции по имени.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя автора для поиска. |

**Возвращаемое значение:**
com.aspose.slides.ICommentAuthor[] - Автор или null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Находит автора в коллекции по имени и инициалам.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя автора для поиска. |
| initials | java.lang.String | Инициалы автора для поиска. |

**Возвращаемое значение:**
com.aspose.slides.ICommentAuthor[] - Автор или null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет автора по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Удаляет первое вхождение указанного автора в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Автор, который будет удалён из коллекции. |

### clear() {#clear--}
```
public abstract void clear()
```


Удаляет всех авторов из коллекции.