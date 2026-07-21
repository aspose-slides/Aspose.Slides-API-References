---
title: Equals()
second_title: Aspose.Slides для C++ – справочник API
description: Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом.
type: docs
weight: 40
url: /ru/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const метод


Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом.

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../) | Объект [TimeSpan](../) для сравнения текущего объекта |

### Возвращаемое значение

True если текущий объект и указанный объект представляют один и тот же интервал времени, иначе - false

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const метод


Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом.

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Объект [TimeSpan](../) для сравнения текущего объекта |

### Возвращаемое значение

True если текущий объект и указанный объект представляют один и тот же интервал времени, иначе - false

## TimeSpan::Equals(TimeSpan, TimeSpan) метод


Возвращает true, если указанные объекты представляют один и тот же интервал времени, иначе - false.

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [TimeSpan](../)
* Класс [Object](../../object/)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)