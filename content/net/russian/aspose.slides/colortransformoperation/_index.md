---
title: ColorTransformOperation
second_title: Aspose.Sildes для .NET API Справочник
description: Определяет операцию преобразования цвета.
type: docs
weight: 2480
url: /ru/aspose.slides/colortransformoperation/
---

## Перечисление ColorTransformOperation

Определяет операцию преобразования цвета.

```csharp
public enum ColorTransformOperation
```

### Значения

| Название | Значение | Описание |
| --- | --- | --- |
| Tint | `0` | Тонирует цвет. Параметр находится в пределах от 0 (оригинальный цвет) до 1 (белый). |
| Shade | `1` | Затемняет цвет. Параметр находится в пределах от 0 (оригинальный цвет) до 1 (черный). |
| Complement | `2` | Изменяет цвет на RGB-дополнительный. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | `3` | Изменяет цвет на инвертированный. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | `4` | Изменяет цвет на серый с той же светлотой. Параметр игнорируется. |
| SetAlpha | `5` | Определяет компонент альфа цвета. Параметр находится в пределах от 0 (прозрачный) до 1 (непрозрачный). |
| AddAlpha | `6` | Добавляет значение параметра к компоненту альфа цвета. Параметр находится в пределах от -1 до 1. |
| MultiplyAlpha | `7` | Умножает компонент альфа на значение параметра. |
| SetHue | `8` | Изменяет компонент оттенка цвета на значение параметра. Параметр находится в пределах от 0 до 360. |
| AddHue | `9` | Добавляет значение параметра к компоненту оттенка цвета. Параметр находится в пределах от -360 до 360. |
| MultiplyHue | `10` | Умножает компонент оттенка на значение параметра. |
| SetSaturation | `11` | Изменяет компонент насыщенности цвета на значение параметра. Параметр находится в пределах от 0 до 1. |
| AddSaturation | `12` | Добавляет значение параметра к компоненту насыщенности цвета. Параметр находится в пределах от -1 до 1. |
| MultiplySaturation | `13` | Умножает компонент насыщенности на значение параметра. |
| SetLuminance | `14` | Изменяет компонент яркости цвета на значение параметра. Параметр находится в пределах от 0 до 1. |
| AddLuminance | `15` | Добавляет значение параметра к компоненту яркости цвета. Параметр находится в пределах от -1 до 1. |
| MultiplyLuminance | `16` | Умножает компонент яркости на значение параметра. |
| SetRed | `17` | Изменяет красный компонент цвета на значение параметра. Параметр находится в пределах от 0 до 1. |
| AddRed | `18` | Добавляет значение параметра к красному компоненту цвета. Параметр находится в пределах от -1 до 1. |
| MultiplyRed | `19` | Умножает красный компонент на значение параметра. |
| SetGreen | `20` | Изменяет зеленый компонент цвета на значение параметра. Параметр находится в пределах от 0 до 1. |
| AddGreen | `21` | Добавляет значение параметра к зеленому компоненту цвета. Параметр находится в пределах от -1 до 1. |
| MultiplyGreen | `22` | Умножает зеленый компонент на значение параметра. |
| SetBlue | `23` | Изменяет синий компонент цвета на значение параметра. Параметр находится в пределах от 0 до 360. |
| AddBlue | `24` | Добавляет значение параметра к синему компоненту цвета. Параметр находится в пределах от -1 до 1. |
| MultiplyBlue | `25` | Умножает синий компонент на значение параметра. |
| Gamma | `26` | Коррекция гаммы. Параметр игнорируется. |
| InverseGamma | `27` | Обратная коррекция гаммы. Параметр игнорируется. |

### Смотрите Так же

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->