---
title: Storage
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет временное хранилище данных для .
type: docs
url: /ru/com.aspose.slides/storage/
---
**Наследование:**
java.lang.Object
```
public final class Storage
```

Представляет временное хранилище данных для [WebDocument](../../com.aspose.slides/webdocument).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Storage()](#Storage--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Помещает значение в хранилище. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Получает данные из хранилища. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Определяет, содержит ли хранилище элемент с указанным ключом. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Помещает значение в хранилище.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для значения. |
| value | TValue | Значение. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Получает данные из хранилища.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ значения. |

**Возвращаемое значение:**
TValue - Значение данных, если оно присутствует в коллекции данных, null otherwise.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Определяет, содержит ли хранилище элемент с указанным ключом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ значения. |

**Возвращаемое значение:**
boolean - True, если хранилище содержит элемент с указанным ключом, иначе false.