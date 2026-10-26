---
title: RoundImpl()
second_title: Aspose.Slides для C++ справка по API
description: Округляет указанное значение до ближайшего значения с заданным числом знаков после запятой. Параметр указывает поведение функции, если указанное значение находится на одинаковом расстоянии от двух ближайших чисел.
type: docs
weight: 287
url: /ru/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) метод

Округляет указанное значение до ближайшего значения с указанным числом знаков после запятой. Параметр указывает поведение функции, если указанное значение находится на одинаковом расстоянии от двух ближайших чисел.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **float** | Значение для округления |
| digits | int | Количество знаков после запятой в округлённом значении |
| mode | [MidpointRounding](../../midpointrounding/) | Указывает, как выполнять округление, если **value** находится на одинаковом расстоянии от двух ближайших чисел. |

### Возвращаемое значение

Число с указанным количеством знаков, ближайшее к **value**

## См. также

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)