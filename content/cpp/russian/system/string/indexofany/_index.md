---
title: IndexOfAny()
second_title: Справочник API Aspose.Slides для C++
description: Поиск символа вперед.
type: docs
weight: 638
url: /ru/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const метод

Поиск символа вперед.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Символ для поиска. |
| startIndex | int | Индекс, с которого начинается поиск. |

### Return Value

Индекс позиции первого символа, начиная с startIndex, или -1, если не найден.

## String::IndexOfAny(const String\&, int) const метод

Соответственно ищет все символы строки str в данном объекте. Если найден первый символ, возвращается его позиция, иначе ищет второй и так далее.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) символов для поиска. Порядок символов имеет значение. |
| startIndex | int | Позиция, с которой начинается поиск. |

### Return Value

Индекс первого найденного символа или -1, если ни один не найден.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const метод

Ищет любой из переданных символов во всей строке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого совпадающего с любым из целевых символов.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |

### Return Value

Индекс первого совпадающего символа или -1, если не найден.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const метод

Ищет любой из переданных символов в подстроке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого совпадающего с любым из целевых символов.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |
| startindex | **int32_t** | Индекс, с которого начинается поиск. |

### Return Value

Индекс первого совпадающего символа или -1, если не найден.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const метод

Ищет любой из переданных символов в подстроке. Сравнивает первый символ строки со всеми символами в anyOf, затем сравнивает второй и так далее. Возвращает индекс первого совпадающего с любым из целевых символов.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) символов для поиска. Порядок не имеет значения. |
| startindex | **int32_t** | Индекс, с которого начинается поиск. |
| count | **int32_t** | Количество символов для просмотра. |

### Return Value

Индекс первого совпадающего символа или -1, если не найден.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)