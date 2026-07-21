---
title: Join()
second_title: Aspose.Slides для C++ справочник API
description: Объединяет массив, используя строку в качестве разделителя.
type: docs
weight: 846
url: /ru/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) метод

Объединяет массив, используя строку в качестве разделителя.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) для размещения между элементами массива при их объединении. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) частей для объединения. |
| startIndex | int | Первый индекс в массиве, с которого начинается объединение. |
| count | int | Количество элементов массива для объединения. -1 означает «до конца массива». |

### Возвращаемое значение

[String](../), представляющий объединённые элементы массива.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) метод

Объединяет массив, используя строку в качестве разделителя.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) для размещения между элементами массива при их объединении. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView частей для объединения. |
| startIndex | int | Первый индекс в массиве, с которого начинается объединение. |
| count | int | Количество элементов массива для объединения. -1 означает «до конца массива». |

### Возвращаемое значение

[String](../), представляющий объединённые элементы массива.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) метод

Объединяет массив, используя строку в качестве разделителя.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) для размещения между элементами массива при их объединении. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - перечислимый объект частей |

### Возвращаемое значение

[String](../), представляющий объединённые элементы.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) метод

Объединяет массив, используя строку в качестве разделителя.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) для размещения между элементами массива при их объединении. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) частей для объединения. |

### Возвращаемое значение

[String](../), представляющий объединённые элементы.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Класс [Object](../../object/)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)