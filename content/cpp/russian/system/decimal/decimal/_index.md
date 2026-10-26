---
title: Decimal()
second_title: Справочник API Aspose.Slides для C++
description: Создает экземпляр, представляющий 0.
type: docs
weight: 1
url: /ru/system/decimal/decimal/
---
## Decimal::Decimal() конструктор

Создает экземпляр, представляющий 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | std::int8_t | 8-битное целочисленное значение, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(std::int16_t) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | std::int16_t | 16-битное целочисленное значение, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(std::int32_t) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | std::int32_t | 32-битное целочисленное значение, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(std::int64_t) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | std::int64_t | 64-битное целочисленное значение, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(std::uint8_t) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | std::uint8_t | беззнаковое 8-битное целочисленное значение, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(std::uint16_t) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | std::uint16_t | беззнаковое 16-битное целочисленное значение, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(std::uint32_t) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | std::uint32_t | беззнаковое 32-битное целочисленное значение, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(std::uint64_t) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | std::uint64_t | беззнаковое 64-битное целочисленное значение, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(float) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(float f)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | **float** | Значение одинарной точности, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(double) конструктор

Создает экземпляр, представляющий указанное значение.

```cpp
System::Decimal::Decimal(double d)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| d | **double** | Значение двойной точности, которое будет представлено объектом [Decimal](../) |

## Decimal::Decimal(const std::string\&) конструктор

Создает экземпляр, представляющий значение, строковое представление которого задано объектом класса std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) конструктор

Создает объект [Decimal](../) из указанных компонентов.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lo | **int32_t** | Нижние 32 бита значения |
| mid | **int32_t** | Средние 32 бита значения |
| hi | **int32_t** | Высшие 32 бита значения |
| isNegative | **bool** | Указывает, является ли значение отрицательным |
| scale | **uint8_t** | Степень 10 в диапазоне от 0 до 28 |

## Decimal::Decimal(const Decimal\&) конструктор

Создает экземпляр класса [Decimal](../), представляющий то же число, что и указанный объект [Decimal](../).

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| d | const [Decimal](../)\& | Объект [Decimal](../), из которого копируется значение |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) конструктор

Создает экземпляр класса [Decimal](../) из массива целых чисел, содержащего двоичное представление.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | Массив целых чисел, содержащий двоичное представление. |

## Decimal::Decimal(std::nullptr_t) конструктор

Всегда генерирует ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) конструктор

Создает экземпляр класса [Decimal](../), представляющий указанное значение.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | Константная ссылка на значение, которое будет представлено объектом, создаваемым конструктором |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)