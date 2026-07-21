---
title: Concat()
second_title: Aspose.Slides для C++ справочник API
description: Объединяет массив строк.
type: docs
weight: 1
url: /ru/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) функция

Объединяет массив строк.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) строк для объединения. |

### Return Value

Объединённая строка.

## System::StringExtra::Concat(const String\&, const String\&) функция

Объединяет строки.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Первая строка для объединения. |
| str1 | const [String](../../system/string/)\& | Вторая строка для объединения. |

### Return Value

Объединённые строки параметров.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) функция

Объединяет строки.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Первая строка для объединения. |
| str1 | const [String](../../system/string/)\& | Вторая строка для объединения. |
| str2 | const [String](../../system/string/)\& | Третья строка для объединения. |

### Return Value

Объединённые строки параметров.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) функция

Объединяет строки.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Первая строка для объединения. |
| str1 | const [String](../../system/string/)\& | Вторая строка для объединения. |
| str2 | const [String](../../system/string/)\& | Третья строка для объединения. |
| str3 | const [String](../../system/string/)\& | Четвёртая строка для объединения. |

### Return Value

Объединённые строки параметров.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) функция

Преобразует несколько объектов в строку и объединяет полученные строки. Специализация для типов [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) для преобразования и объединения. |

### Return Value

Значение [String](../../system/string/) полученное объединением строковых представлений всех переданных объектов.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) функция

Преобразует несколько объектов в строку и объединяет полученные строки. Специализация для арифметических типов.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) для преобразования и объединения. |

### Return Value

Значение [String](../../system/string/) полученное объединением строковых представлений всех переданных объектов.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) функция

Преобразует несколько объектов в строку и объединяет полученные строки. Специализация для структур и других типовых значений.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) для преобразования и объединения. |

### Return Value

Значение [String](../../system/string/) полученное объединением строковых представлений всех переданных объектов.

## См. также

* Typedef [ArrayPtr](../../system/arrayptr/)
* Класс [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Пространство имён [System::StringExtra](../)
* Library [Aspose.Slides](../../)