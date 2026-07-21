---
title: String()
second_title: Справочник API Aspose.Slides для C++
description: Конструктор по умолчанию. Создаёт объект строки, который считается null.
type: docs
weight: 14
url: /ru/system/string/string/
---
## String::String() конструктор

Конструктор по умолчанию. Создает объект строки, который считается null.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) конструктор

Создает строку на основе строкового литерала. Рассматривает литерал как нуль-терминированную строку, вычисляет длину целевой строки по размеру литерала.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T\& | [String](../) указатель литерала. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) конструктор

Создает строку на основе указателя на строку символов. Рассматривает строку как нуль-терминированную, вычисляет длину целевой строки по нулевому символу.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | Указатель на строку символов. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) конструктор

Создает строку на основе строкового литерала. Рассматривает литерал как нуль-терминированную строку в UTF-8, вычисляет длину целевой строки по размеру литерала.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T\& | [String](../) указатель литерала. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) конструктор

Создает строку на основе указателя на строку символов. Рассматривает строку как нуль-терминированную в UTF-8, вычисляет длину целевой строки по нулевому символу.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | Указатель на строку символов. |

## String::String(const char16_t *, int) конструктор

Создает строку из указателя на строку символов и явной длины.

```cpp
System::String::String(const char16_t *str, int length)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const char16_t * | [String](../) указатель, может быть литералом или массивом. |
| length | int | Явная длина строки |

## String::String(const ReadOnlySpan\<char16_t\>\&) конструктор

Инициализирует новый экземпляр класса [System.String](../) символами Unicode, указанными в заданном только для чтения диапазоне.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Только для чтения диапазон символов Unicode. |

## String::String(const char *, int) конструктор

Создает строку из указателя на строку символов и явной длины.

```cpp
System::String::String(const char *str, int length)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const char * | [String](../) указатель на данные UTF-8, может быть литералом или массивом. |
| length | int | Явная длина строки |

## String::String(const char16_t *, int, int) конструктор

Создает строку из указателя на строку символов, начиная с позиции `start` и используя длину `length`.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const char16_t * | [String](../) указатель, может быть литералом или массивом. |
| start | int | Начальная позиция. |
| length | int | [String](../) длина. |

## String::String(const char16_t, int) конструктор

Конструктор заполнения.

```cpp
System::String::String(const char16_t ch, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | const char16_t | Символ заполнения. |
| count | int | Целевая длина. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) конструктор

Конструктор nullptr. Объявлен как шаблон для разрешения приоритетов с другими шаблонными конструкторами.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Должен быть типа nullptr_t |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) конструктор

Создает строку на основе широкого строкового литерала. Рассматривает литерал как нуль-терминированную строку, вычисляет длину целевой строки по размеру литерала. Преобразование из **wchar_t** трудоемко на некоторых платформах, поэтому не допускаются неявные преобразования.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T\& | [String](../) указатель литерала. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) конструктор

Создает строку на основе указателя на широкую строку. Рассматривает строку как нуль-терминированную, вычисляет длину целевой строки по нулевому символу. Преобразование из **wchar_t** трудоемко на некоторых платформах, поэтому не допускаются неявные преобразования.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | Указатель на строку символов. |

## String::String(const wchar_t *, int) конструктор

Создает строку из указателя на широкую строку и явной длины. Преобразование из **wchar_t** трудоемко на некоторых платформах, поэтому не допускаются неявные преобразования.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) указатель, может быть литералом или массивом. |
| length | int | Явная длина строки |

## String::String(const wchar_t, int) конструктор

Конструктор заполнения. Преобразование из **wchar_t** трудоемко на некоторых платформах, поэтому не допускаются неявные преобразования.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | const **wchar_t** | Символ заполнения. |
| count | int | Целевая длина. |

## String::String(const String\&) конструктор

Конструктор копирования.

```cpp
System::String::String(const String &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) для копирования. |

## String::String(String\&&) конструктор

Конструктор перемещения.

```cpp
System::String::String(String &&str) noexcept
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) для перемещения данных из. |

## String::String(const ArrayPtr\<char16_t\>\&) конструктор

Преобразует весь массив символов в строку.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) для преобразования в строку. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) конструктор

Преобразует подмассив символов в строку. Если параметры выходят за границы массива, создаётся пустая строка.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Массив символов. |
| offset | int | Индекс начала подмассива. |
| len | int | Длина подмассива. |

## String::String(const codeporting_icu::UnicodeString\&) конструктор

Оборачивает UnicodeString в [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString для оборачивания в [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) конструктор

Конструктор перемещения.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString для оборачивания в [String](../). |

## String::String(const std::wstring\&) конструктор

Создаёт [String](../) из широких строк.

```cpp
System::String::String(const std::wstring &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const std::wstring\& | Широкая строка для преобразования в [String](../). |

## String::String(const std::u16string\&) конструктор

Создаёт [String](../) из строки utf16.

```cpp
System::String::String(const std::u16string &str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const std::u16string\& | Utf16-строка для преобразования в [String](../). |

## String::String(const std::string\&) конструктор

Создаёт [String](../) из std::string, представленной в формате UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| utf8str | const std::string\& | std::string для преобразования в [String](../). |

## String::String(const std::u32string\&) конструктор

Создаёт [String](../) из std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string для преобразования в [String](../). |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [String](../)
* Класс [ReadOnlySpan](../../readonlyspan/)
* Структура [IsStringLiteral](../../isstringliteral/)
* Структура [IsStringPointer](../../isstringpointer/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)