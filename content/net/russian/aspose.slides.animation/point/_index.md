---
title: Point
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет точку анимации.
type: docs
weight: 620
url: /ru/aspose.slides.animation/point/
---
## Point class

Представляет точку анимации.

```csharp
public class Point : IPoint
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Point](point#constructor)() | Конструктор по умолчанию. |
| [Point](point#constructor_1)(float, object, string) | Создать точку анимации со временем, значением и формулой. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Formula](../../aspose.slides.animation/point/formula) { get; set; } | Формулы внутри значений, от, до, по атрибутам могут состоять из следующих: Стандартные арифметические операторы:'+', '-' , '*', '/', '^', '%' (mod) Константы:'pi' 'e' Условные операторы:'abs', 'min ', 'Максимум', '?' (if) Операторы сравнения:'==', '&gt;=', '', '!=', '!' Тригонометрические операторы:'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (свойства, поддерживаемые хостом) например:"#ppt_x+(cos(-2*pi *(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Чтение/записьString. |
| [Time](../../aspose.slides.animation/point/time) { get; set; } | Представляет значение времени. Чтение/записьSingle. |
| [Value](../../aspose.slides.animation/point/value) { get; set; } | Представляет значение в очках. Только:bool, ColorFormat, float, int, string. Чтение/записьObject. |

### Смотрите также

* interface [IPoint](../ipoint)
* пространство имен [Aspose.Slides.Animation](../../aspose.slides.animation)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
