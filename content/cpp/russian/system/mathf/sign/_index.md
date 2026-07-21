---
title: Sign()
second_title: Aspose.Slides для C++ справочник API
description: Определяет знак указанного знакового целого значения.
type: docs
weight: 274
url: /ru/system/mathf/sign/
---
## MathF::Sign(T) метод

Определяет знак указанного знакового целого значения.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Знаковый целочисленный тип |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T | Значение, знак которого необходимо определить |

### Возвращаемое значение

- 1 если **value** меньше 0; 0 если **value** равно 0; 1 если **value** больше 0

## MathF::Sign(T) метод

Определяет знак указанного значения с плавающей точкой.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип аргумента с плавающей точкой |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T | Значение, знак которого необходимо определить |

### Возвращаемое значение

- 1 если **value** меньше 0; 0 если **value** равно 0; 1 если **value** больше 0

## См. также

* Структура [MathF](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)