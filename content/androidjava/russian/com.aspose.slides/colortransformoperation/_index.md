---
title: ColorTransformOperation
second_title: Справочник API Aspose.Slides для Android на Java
description: Определяет операцию преобразования цвета.
type: docs
url: /ru/com.aspose.slides/colortransformoperation/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Определяет операцию преобразования цвета.
## Поля

| Поле | Описание |
| --- | --- |
| [Tint](#Tint) | Тонирует цвет. |
| [Shade](#Shade) | Затемняет цвет. |
| [Complement](#Complement) | Изменяет цвет на RGB-комплементарный. |
| [Inverse](#Inverse) | Изменяет цвет на инвертированный. |
| [Grayscale](#Grayscale) | Изменяет цвет на серый с той же яркостью. |
| [SetAlpha](#SetAlpha) | Определяет альфа-компонент цвета. |
| [AddAlpha](#AddAlpha) | Добавляет значение параметра к альфа-компоненту цвета. |
| [MultiplyAlpha](#MultiplyAlpha) | Умножает альфа-компонент на значение параметра. |
| [SetHue](#SetHue) | Изменяет компонент оттенка цвета на значение параметра. |
| [AddHue](#AddHue) | Добавляет значение параметра к компоненту оттенка цвета. |
| [MultiplyHue](#MultiplyHue) | Умножает компонент оттенка на значение параметра. |
| [SetSaturation](#SetSaturation) | Изменяет компонент насыщенности цвета на значение параметра. |
| [AddSaturation](#AddSaturation) | Добавляет значение параметра к компоненту насыщенности цвета. |
| [MultiplySaturation](#MultiplySaturation) | Умножает компонент насыщенности на значение параметра. |
| [SetLuminance](#SetLuminance) | Изменяет компонент яркости цвета на значение параметра. |
| [AddLuminance](#AddLuminance) | Добавляет значение параметра к компоненту яркости цвета. |
| [MultiplyLuminance](#MultiplyLuminance) | Умножает компонент яркости на значение параметра. |
| [SetRed](#SetRed) | Изменяет красный компонент цвета на значение параметра. |
| [AddRed](#AddRed) | Добавляет значение параметра к красному компоненту цвета. |
| [MultiplyRed](#MultiplyRed) | Умножает красный компонент на параметр. |
| [SetGreen](#SetGreen) | Изменяет зеленый компонент цвета на значение параметра. |
| [AddGreen](#AddGreen) | Добавляет параметр к зеленому компоненту цвета. |
| [MultiplyGreen](#MultiplyGreen) | Умножает зеленый компонент цвета на значение параметра. |
| [SetBlue](#SetBlue) | Изменяет синий компонент цвета на значение параметра. |
| [AddBlue](#AddBlue) | Добавляет значение параметра к синему компоненту цвета. |
| [MultiplyBlue](#MultiplyBlue) | Умножает синий компонент цвета на значение параметра. |
| [Gamma](#Gamma) | Гамма-коррекция. |
| [InverseGamma](#InverseGamma) | Обратная гамма-коррекция. |
### Тонирование {#Tint}
```
public static final int Tint
```

Тонирует цвет. Параметр находится в диапазоне от 0 (исходный цвет) до 1 (белый).

### Затемнение {#Shade}
```
public static final int Shade
```

Затемняет цвет. Параметр находится в диапазоне от 0 (исходный цвет) до 1 (чёрный).

### Дополнение {#Complement}
```
public static final int Complement
```

Изменяет цвет на RGB-комплементарный. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Инверсия {#Inverse}
```
public static final int Inverse
```

Изменяет цвет на инвертированный. r = 1 - r; g = 1 - g; b = 1 - b;

### Оттенки серого {#Grayscale}
```
public static final int Grayscale
```

Изменяет цвет на серый с той же яркостью. Параметр игнорируется.

### Установить альфа {#SetAlpha}
```
public static final int SetAlpha
```

Определяет альфа-компонент цвета. Параметр находится в диапазоне от 0 (прозрачный) до 1 (непрозрачный).

### Добавить альфа {#AddAlpha}
```
public static final int AddAlpha
```

Добавляет значение параметра к альфа-компоненту цвета. Параметр находится в диапазоне от -1 до 1.

### Умножить альфа {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Умножает альфа-компонент на значение параметра.

### Установить оттенок {#SetHue}
```
public static final int SetHue
```

Изменяет компонент оттенка цвета на значение параметра. Параметр находится в диапазоне от 0 до 360.

### Добавить оттенок {#AddHue}
```
public static final int AddHue
```

Добавляет значение параметра к компоненту оттенка цвета. Параметр находится в диапазоне от -360 до 360.

### Умножить оттенок {#MultiplyHue}
```
public static final int MultiplyHue
```

Умножает компонент оттенка на значение параметра.

### Установить насыщенность {#SetSaturation}
```
public static final int SetSaturation
```

Изменяет компонент насыщенности цвета на значение параметра. Параметр находится в диапазоне от 0 до 1.

### Добавить насыщенность {#AddSaturation}
```
public static final int AddSaturation
```

Добавляет значение параметра к компоненту насыщенности цвета. Параметр находится в диапазоне от -1 до 1.

### Умножить насыщенность {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Умножает компонент насыщенности на значение параметра.

### Установить яркость {#SetLuminance}
```
public static final int SetLuminance
```

Изменяет компонент яркости цвета на значение параметра. Параметр находится в диапазоне от 0 до 1.

### Добавить яркость {#AddLuminance}
```
public static final int AddLuminance
```

Добавляет значение параметра к компоненту яркости цвета. Параметр находится в диапазоне от -1 до 1.

### Умножить яркость {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Умножает компонент яркости на значение параметра.

### Установить красный {#SetRed}
```
public static final int SetRed
```

Изменяет красный компонент цвета на значение параметра. Параметр находится в диапазоне от 0 до 1.

### Добавить красный {#AddRed}
```
public static final int AddRed
```

Добавляет значение параметра к красному компоненту цвета. Параметр находится в диапазоне от -1 до 1.

### Умножить красный {#MultiplyRed}
```
public static final int MultiplyRed
```

Умножает красный компонент на параметр.

### Установить зеленый {#SetGreen}
```
public static final int SetGreen
```

Изменяет зеленый компонент цвета на значение параметра. Параметр находится в диапазоне от 0 до 1.

### Добавить зеленый {#AddGreen}
```
public static final int AddGreen
```

Добавляет параметр к зеленому компоненту цвета. Параметр находится в диапазоне от -1 до 1.

### Умножить зеленый {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Умножает зеленый компонент цвета на значение параметра.

### Установить синий {#SetBlue}
```
public static final int SetBlue
```

Изменяет синий компонент цвета на значение параметра. Параметр находится в диапазоне от 0 до 360.

### Добавить синий {#AddBlue}
```
public static final int AddBlue
```

Добавляет значение параметра к синему компоненту цвета. Параметр находится в диапазоне от -1 до 1.

### Умножить синий {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Умножает синий компонент цвета на значение параметра.

### Гамма {#Gamma}
```
public static final int Gamma
```

Гамма-коррекция. Параметр игнорируется.

### Обратная гамма {#InverseGamma}
```
public static final int InverseGamma
```

Обратная гамма-коррекция. Параметр игнорируется.