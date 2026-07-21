---
title: IsNullOrEmpty()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, является ли коллекция null или пустой.
type: docs
weight: 27
url: /ru/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) метод


Проверяет, является ли коллекция null или пустой.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип коллекции. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Коллекция для проверки. |

### Возвращаемое значение

True если коллекция null или имеет нулевой подсчёт элементов, false в противном случае.

## TestTools::IsNullOrEmpty(const System::String\&) метод


Проверяет, является ли строка null или пустой.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) для проверки. |

### Возвращаемое значение

True если строка null или имеет нулевую длину, false в противном случае.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)