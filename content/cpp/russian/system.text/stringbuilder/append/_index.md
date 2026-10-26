---
title: Append()
second_title: Aspose.Slides для C++ справка API
description: Добавляет символ в builder.
type: docs
weight: 118
url: /ru/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) метод

Adds character to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Значение символа. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(char_t, int) метод

Adds characters to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Значение символа. |
| count | int | Сколько раз повторять вставляемый символ. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) метод

Adds characters array to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Символы для добавления. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) метод

Adds characters array slice to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Символы для добавления. |
| startIndex | int | Индекс начала среза. |
| charCount | int | Длина среза. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(const String\&) метод

Adds string to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) для добавления. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(const String\&, int, int) метод

Adds string slice to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) для добавления. |
| startIndex | int | Индекс начала среза. |
| charCount | int | Длина среза. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(const SharedPtr\<T\>\&) метод

Adds object's string representation to builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) для сериализации и добавления. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) метод

Adds builder's content to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder, из которого добавляется содержимое. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(float) метод

Adds floating point value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | **float** | Значение для сериализации и добавления. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(double) метод

Adds floating point value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| df | **double** | Значение для сериализации и добавления. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(int) метод

Adds integer value to builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | int | Значение для сериализации и добавления. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(T) метод

Adds arithmetic value to builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Арифметический тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T | Значение для сериализации и добавления. |

### Возвращаемое значение

Этот указатель.

## StringBuilder::Append(E) метод

Adds enum value string representation to builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| E | [Enum](../../../system/enum/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| e | E | Значение для сериализации и добавления. |

### Возвращаемое значение

Этот указатель.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)