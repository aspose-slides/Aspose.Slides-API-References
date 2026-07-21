---
title: Split()
second_title: Справочник API Aspose.Slides для C++
description: Разбивает строку по символу.
type: docs
weight: 768
url: /ru/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const method

Разбивает строку по символу.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | char_t | Символ, по которому разбивается строка. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## String::Split(char_t, int32_t, StringSplitOptions) const method

Разбивает строку по символу.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | char_t | Символ, по которому разбивается строка. |
| count | **int32_t** | Максимальное количество возвращаемых подстрок. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## String::Split(char_t, char_t, StringSplitOptions) const method

Разбивает строку по одному из двух символов.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorA | char_t | Первый символ, по которому разбивается строка. |
| separatorB | char_t | Второй символ, по которому разбивается строка. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method

Разбивает строку по одному из указанных символов.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) символов-разделителей. Если пусто, любой пробельный символ считается разделителем. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method

Разбивает строку по одному из указанных символов.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) символов-разделителей. Если пусто, любой пробельный символ считается разделителем. |
| count | **int32_t** | Максимальное количество возвращаемых подстрок. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## String::Split(const String\&, StringSplitOptions) const method

Разбивает строку по подстроке.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const [String](../)\& | Подстрока, выступающая в роли разделителя. Если пусто, пробельный символ выступает как разделитель. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## String::Split(const String\&, int, StringSplitOptions) const method

Разбивает строку по подстроке.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const [String](../)\& | Подстрока, выступающая в роли разделителя. Если пусто, пробельный символ выступает как разделитель. |
| count | int | Максимальное количество элементов в массиве разделений. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method

Разбивает строку по подстроке.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) строк-разделителей. Если пусто, разделение не выполняется. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method

Разбивает строку по подстроке. В настоящее время поддерживается только массив разделителей из нуля или одного элемента.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) строк-разделителей. Если пусто, разделение не выполняется. |
| count | int | Максимальное количество элементов в массиве разделений. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Параметры разделения. |

### Возвращаемое значение

[Array](../../array/) подстрок.

## Смотрите также

* Перечисление [StringSplitOptions](../../stringsplitoptions/)
* Тип-определение [ArrayPtr](../../arrayptr/)
* Класс [String](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)