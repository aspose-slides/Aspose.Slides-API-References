---
title: Exists()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, содержит ли указанный объект Array элемент, удовлетворяющий требованиям указанного предиката.
type: docs
weight: 781
url: /ru/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) метод


Определяет, содержит ли указанный объект [Array](../) элемент, удовлетворяющий требованиям указанного предиката.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Массив, в котором искать элемент |
| match | std::function\<**bool**(T)> | Объект функции, определяющий требования и проверяющий, удовлетворяет ли элемент им |

### Возвращаемое значение

Истина, если **arr** содержит элемент, удовлетворяющий требованиям, определённым **match**

## Смотрите также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)