---
title: CompareTo()
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает текущий объект и указанные объекты.
type: docs
weight: 27
url: /ru/system/timespan/compareto/
---
## TimeSpan::CompareTo(TimeSpan) const метод

Сравнивает текущий объект и указанный объект.

```cpp
constexpr int System::TimeSpan::CompareTo(TimeSpan value) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TimeSpan](../) | Объект [TimeSpan](../) для сравнения с текущим объектом |

### Возвращаемое значение

- 1 если текущий объект представляет интервал, который короче **value**; 0 если текущий объект представляет интервал, равный **value**; 1 если текущий объект представляет интервал, который длиннее **value**

## TimeSpan::CompareTo(const SharedPtr\<Object\>\&) const метод

Сравнивает текущий объект и указанный объект.

```cpp
int System::TimeSpan::CompareTo(const SharedPtr<Object> &obj) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Объект [TimeSpan](../) для сравнения с текущим объектом |

### Возвращаемое значение

- 1 если текущий объект представляет интервал, который короче **value**; 0 если текущий объект представляет интервал, равный **value**; 1 если текущий объект представляет интервал, который длиннее **value**

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [TimeSpan](../)
* Класс [Object](../../object/)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)