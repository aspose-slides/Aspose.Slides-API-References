---
title: Compare()
second_title: Aspose.Slides для справочника API C++
description: Сравнивает два значения.
type: docs
weight: 2692
url: /ru/system/compare/
---
## System::Compare(const TA\&, const TB\&) функция

Сравнивает два значения.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TA | Тип первого сравниваемого |
| TB | Тип второго сравниваемого |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const TA\& | Первый сравниваемый |
| b | const TB\& | Второй сравниваемый |

### Возвращаемое значение

- 1 если **a** меньше **b**; 0 если значения равны; 1 если **a** больше **b**

## System::Compare(const TA\&, const TB\&) функция

Сравнивает два числа с плавающей запятой.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TA | Тип первого сравниваемого |
| TB | Тип второго сравниваемого |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const TA\& | Первый сравниваемый |
| b | const TB\& | Второй сравниваемый |

### Возвращаемое значение

- 1 если **a** меньше **b**; 0 если значения равны; 1 если **a** больше **b**

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)