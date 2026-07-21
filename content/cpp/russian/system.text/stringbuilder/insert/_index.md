---
title: Insert()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет строку в фиксированную позицию билдера.
type: docs
weight: 183
url: /ru/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) метод


Вставляет строку в фиксированную позицию билдера.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Позиция, в которую вставляются символы. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) для вставки. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Insert(int32_t, const String\&, int32_t) метод


Вставляет повторяющуюся строку в фиксированную позицию бил

дера.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция, в которую вставляются символы. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) для вставки. |
| count | **int32_t** | Сколько раз повторять строку **value**. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Insert(int, char_t) метод


Вставляет символ в фиксированную позицию билдера.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Позиция, в которую вставляются символы. |
| ch | char_t | Символ для вставки. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) метод


Вставляет символы в фиксированную позицию билдера.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция, в которую вставляются символы. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) для вставки среза из. |
| startIndex | int | [Array](../../../system/array/) начальный индекс среза. |
| charCount | int | [Array](../../../system/array/) длина среза. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Insert(int, T) метод


Вставляет значение в фиксированную позицию билдера.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Parameter | тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Позиция, в которую вставляются символы. |
| value | T | Значение для форматирования и вставки. |

### Возвращаемое значение

Этот указатель.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [StringBuilder](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Text](../../)
* Library [Aspose.Slides](../../../)