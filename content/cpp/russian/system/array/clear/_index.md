---
title: Clear()
second_title: Справочник API Aspose.Slides для C++
description: Не поддерживается, потому что массив, представленный текущим объектом, является только для чтения.
type: docs
weight: 53
url: /ru/system/array/clear/
---
## Array::Clear() метод

Не поддерживается, потому что массив, представленный текущим объектом, является только для чтения.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) метод

Заменяет **count** значений, начиная с индекса **startIndex**, в указанном массиве значениями по умолчанию.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Type | Тип элементов в целевом массиве |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Целевой массив |
| startIndex | int | Индекс, с которого начинается замена элементов |
| count | int | Количество элементов для замены |

## См. также

* Тип [ArrayPtr](../../arrayptr/)
* Метод [Type](../../object/type/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)