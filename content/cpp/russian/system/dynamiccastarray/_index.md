---
title: DynamicCastArray()
second_title: Aspose.Slides для C++ справка API
description: Выполняет приведение элементов указанного массива к другому типу.
type: docs
weight: 2952
url: /ru/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) function


Выполняет приведение элементов указанного массива к другому типу.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| To | Тип, к которому нужно привести элементы указанного массива |
| From | Тип элементов массива, элементы которого нужно привести |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Умный указатель на массив, содержащий элементы для приведения |

### Возвращаемое значение

Указатель на новый массив, содержащий элементы типа **To**, эквивалентные элементам **from**

Устарело
:   Добавлен для обратной совместимости. Используйте ExplicitCast вместо него.

## Смотрите также

* Typedef [SharedPtr](../sharedptr/)
* Класс [Array](../array/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)