---
title: Format()
second_title: Aspose.Slides для C++: справочник API
description: Форматирует строку в стиле C#.
type: docs
weight: 885
url: /ru/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method

Форматирует строку в стиле C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Args | Аргументы для форматирования строки. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Провайдер формата, используемый для преобразования аргументов в строки. |
| format | const [String](../)\& | Строка формата. |
| args | const Args\&... | Аргументы для форматирования строки. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method

Форматирует строку в стиле C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Args | Аргументы для форматирования строки. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | std::nullptr_t | Строка формата. |
| args | const [String](../)\& | Аргументы для форматирования строки. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method

Форматирует строку в стиле C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Args | Аргументы для форматирования строки. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | std::nullptr_t | Строка формата. |
| args | const char16_t(&) | Аргументы для форматирования строки. |

## String::Format(const String\&, const Args\&...) method

Форматирует строку в стиле C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Args | Аргументы для форматирования строки. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../)\& | Строка формата. |
| args | const Args\&... | Аргументы для форматирования строки. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method

Форматирует строку в стиле C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Аргументы для форматирования строки. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../)\& | Строка формата. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Аргументы для форматирования строки. |

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Класс [String](../)
* Класс [IFormatProvider](../../iformatprovider/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)