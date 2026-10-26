---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides для C++ справочник API
description: Вспомогательная функция для определения, имеет ли конкретный класс оператор ==.
type: docs
weight: 235
url: /ru/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) function


Вспомогательная функция для определения, имеет ли конкретный класс оператор ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип для проверки. |
| Dummy | Фиктивный аргумент для магии SFINAE. |

### Возвращаемое значение

Значение std::true_type, если оператор == присутствует, иначе false.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) function


Вспомогательная функция для определения, имеет ли конкретный класс оператор ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```


### Возвращаемое значение

Значение std::true_type, если оператор == присутствует, иначе false.

## См. также

* Пространство имён [System::Collections::Generic::Details](../)
* Библиотека [Aspose.Slides](../../)