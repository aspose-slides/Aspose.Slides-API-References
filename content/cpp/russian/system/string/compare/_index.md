---
title: Compare()
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает две подстроки, определяя меньше, равно или больше.
type: docs
weight: 820
url: /ru/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) метод

Сравнивает две подстроки, определяя меньше, равно или больше.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| indexA | int | Начало первой подстроки строки. |
| strB | const [String](../)\& | Вторая строка для сравнения. |
| indexB | int | Начало второй подстроки строки. |
| length | int | Количество символов для сравнения. |
| ignoreCase | **bool** | Указывает, должно ли сравнение быть без учёта регистра. |

### Возвращаемое значение

Отрицательное значение, если первая подстрока меньше второй, ноль, если они равны, положительное значение в остальных случаях.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) метод

Сравнивает две подстроки, определяя меньше, равно или больше.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| indexA | int | Начало первой подстроки строки. |
| strB | const [String](../)\& | Вторая строка для сравнения. |
| indexB | int | Начало второй подстроки строки. |
| length | int | Количество символов для сравнения. |
| ignoreCase | **bool** | Указывает, должно ли сравнение быть без учёта регистра. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая для сравнения. |

### Возвращаемое значение

Отрицательное значение, если первая подстрока меньше второй, ноль, если они равны, положительное значение в остальных случаях.

## String::Compare(const String\&, const String\&, System::StringComparison) метод

Сравнивает две строки, определяя меньше, равно или больше.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| strB | const [String](../)\& | Вторая строка для сравнения. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

Отрицательное значение, если первая подстрока меньше второй, ноль, если они равны, положительное значение в остальных случаях.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) метод

Сравнивает две строки, определяя меньше, равно или больше.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| indexA | int | Начало первой подстроки строки. |
| strB | const [String](../)\& | Вторая строка для сравнения. |
| indexB | int | Начало второй подстроки строки. |
| length | int | Количество символов для сравнения. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

Отрицательное значение, если первая подстрока меньше второй, ноль, если они равны, положительное значение в остальных случаях.

## String::Compare(const String\&, const String\&, bool) метод

Сравнивает две строки, определяя меньше, равно или больше.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| strB | const [String](../)\& | Вторая строка для сравнения. |
| ignoreCase | **bool** | Указывает, должно ли сравнение быть без учёта регистра. |

### Возвращаемое значение

Отрицательное значение, если первая подстрока меньше второй, ноль, если они равны, положительное значение в остальных случаях.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) метод

Сравнивает две строки, определяя меньше, равно или больше.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| strB | const [String](../)\& | Вторая строка для сравнения. |
| ignoreCase | **bool** | Указывает, должно ли сравнение быть без учёта регистра. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, используемая для сравнения. |

### Возвращаемое значение

Отрицательное значение, если первая подстрока меньше второй, ноль, если они равны, положительное значение в остальных случаях.

## См. также

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)