---
title: ToBoolean()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает указанное логическое значение.
type: docs
weight: 79
url: /ru/system/convert/toboolean/
---
## Convert::ToBoolean(bool) метод


Возвращает указанное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) метод


Преобразует указанное беззнаковое 8-битное целое в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) метод


Преобразует указанное знаковое 8-битное целое в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) метод


Преобразует указанное беззнаковое 16-битное целое в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) метод


Преобразует указанное знаковое 16-битное целое в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) метод


Преобразует указанное беззнаковое 32-битное целое в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) метод


Преобразует указанное знаковое 32-битное целое в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) метод


Преобразует указанное беззнаковое 64-битное целое в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) метод


Преобразует указанное знаковое 64-битное целое в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) метод


Преобразует указанное число с плавающей запятой одинарной точности в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) метод


Преобразует указанное число с плавающей запятой двойной точности в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) метод


Преобразует указанное десятичное число в эквивалентное логическое значение.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) метод


Преобразование не поддерживается. Всегда бросает InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) метод


Преобразование не поддерживается. Всегда бросает InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) метод


Преобразует указанную нулевую строку в эквивалентное логическое значение.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Возвращаемое значение

False.

## Convert::ToBoolean(const char_t *) метод


Преобразует указанную C-строку в значение типа bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для преобразования |

### Возвращаемое значение

True, если указанная C-строка равна "True", и false, если указанная C-строка равна "False".

## Convert::ToBoolean(const String\&) метод


Преобразует указанную строку в значение типа bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

True, если указанная C-строка равна "True", и false, если указанная строка равна "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанную строку в значение типа bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Строка для преобразования |

### Возвращаемое значение

True, если указанная C-строка равна "True", и false, если указанная строка равна "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) метод


Преобразует указанное упакованное значение в эквивалентное логическое значение.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Умный указатель на объект, упаковывающий значение для преобразования |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Формат строки, используемый, если тип упакованного значения — [String](../../string/) |

### Возвращаемое значение

Логическое значение, эквивалентное указанному упакованному значению

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)