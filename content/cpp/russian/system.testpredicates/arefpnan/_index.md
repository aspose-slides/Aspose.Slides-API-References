---
title: AreFPNaN()
second_title: Справочник API Aspose.Slides для C++
description: пространство имён Details
type: docs
weight: 1
url: /ru/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) function


namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Возвращаемое значение

Истина, если **lhs** и **rhs** являются значениями с плавающей точкой, иначе — ложь.
## Замечания


Проверяет, что два значения с плавающей точкой оба являются NaN. Обрабатывает ситуацию, когда поддерживается не сигнализующий NaN. 
## System::TestPredicates::AreFPNaN(T1, T2) function


Проверяет, что два значения с плавающей точкой оба являются NaN. Обрабатывает ситуацию, когда не сигнализующий NaN не поддерживается.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Возвращаемое значение

Всегда возвращает false, так как значение NaN не поддерживается.

## См. также

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)