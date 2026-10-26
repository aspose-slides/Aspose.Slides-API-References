---
title: operator+()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает новый экземпляр класса Decimal, представляющий значение, которое является суммой указанного значения и значения, представленного указанным объектом Decimal.
type: docs
weight: 2159
url: /ru/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) функция

Возвращает новый экземпляр класса [Decimal](../decimal/), представляющий значение, являющееся суммой указанного значения и значения, представляемого указанным объектом [Decimal](../decimal/).

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const T\& | Первый слагаемый |
| d | const [Decimal](../decimal/)\& | Константная ссылка на объект [Decimal](../decimal/), представляющий второй слагаемый |

### Возвращаемое значение

Новый экземпляр класса [Decimal](../decimal/), представляющий значение, которое является суммой **x** и значения, представленного **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) функция

Подключает все обратные вызовы из делегата правой руки к концу списка обратных вызовов делегата левой руки.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Делегат, к которому добавляются обратные вызовы. |
| rhv | MulticastDelegate\<T\> | Делегат, чьи обратные вызовы добавляются. |

### Возвращаемое значение

Возвращает делегат, содержащий обратные вызовы левого значения, а затем правого.

## System::operator+(const T1\&, const Nullable\<T2\>\&) функция

Складывает значения, которые не являются nullable, и nullable.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип левого операнда. |
| T2 | Тип правого операнда. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| some | const T1\& | Левый операнд. |
| other | const [Nullable](../nullable/)\<T2\>\& | Правый операнд. |

### Возвращаемое значение

Результат сложения.

## System::operator+(T\&, const String\&) функция

[String](../string/) конкатенация.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [String](../string/) тип литерала. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | T\& | Литерал, который нужно конкатенировать со строкой. |
| right | const [String](../string/)\& | [String](../string/) для конкатенации. |

### Возвращаемое значение

Конкатенированная строка.

## System::operator+(T\&, const String\&) функция

[String](../string/) конкатенация.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [String](../string/) тип указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | T\& | Указатель [String](../string/) для конкатенации со строкой. |
| right | const [String](../string/)\& | [String](../string/) для конкатенации. |

### Возвращаемое значение

Конкатенированная строка.

## System::operator+(const char_t, const String\&) функция

[String](../string/) конкатенация.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | const char_t | Символ, который нужно конкатенировать со строкой. |
| right | const [String](../string/)\& | [String](../string/) для конкатенации. |

### Возвращаемое значение

Конкатенированная строка.

## См. также

* Класс [Decimal](../decimal/)
* Класс [Nullable](../nullable/)
* Класс [String](../string/)
* Структура [IsStringLiteral](../isstringliteral/)
* Структура [IsStringPointer](../isstringpointer/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)