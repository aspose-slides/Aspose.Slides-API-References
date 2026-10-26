---
title: CommentAuthorCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию авторов комментариев.
type: docs
url: /ru/com.aspose.slides/commentauthorcollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Represents a collection of comment authors.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Добавляет нового автора в конец коллекции. |
| [toArray()](#toArray--) | Создает и возвращает массив со всеми авторами. |
| [findByName(String name)](#findByName-java.lang.String-) | Находит автора в коллекции по имени. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Находит автора в коллекции по имени и инициалам. |
| [removeAt(int index)](#removeAt-int-) | Удаляет автора по указанному индексу в коллекции. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Удаляет первое вхождение указанного автора в коллекции. |
| [clear()](#clear--) | Удаляет всех авторов из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасно). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
### size() {#size--}
```
public final int size()
```

Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращает:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Добавляет нового автора в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя нового автора. |
| initials | java.lang.String | Инициалы нового автора. |

**Возвращает:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Новый объект [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Создает и возвращает массив со всеми авторами.

**Возвращает:**
com.aspose.slides.ICommentAuthor[] - Массив [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Находит автора в коллекции по имени.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя автора для поиска. |

**Возвращает:**
com.aspose.slides.ICommentAuthor[] - Автор или null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Находит автора в коллекции по имени и инициалам.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя автора для поиска. |
| initials | java.lang.String | Инициалы автора для поиска. |

**Возвращает:**
com.aspose.slides.ICommentAuthor[] - Автор или null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет автора по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Удаляет первое вхождение указанного автора в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Автор, которого следует удалить из коллекции. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет всех авторов из коллекции.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасно). Только для чтения boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object