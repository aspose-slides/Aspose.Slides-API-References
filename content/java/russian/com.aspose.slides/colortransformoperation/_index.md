---
title: ColorTransformOperation
second_title: Справочник API Aspose.Slides для Java
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
| [SetHue](#SetHue) | Изменяет оттенок (hue) цвета на значение параметра. |
| [AddHue](#AddHue) | Добавляет значение параметра к оттенку цвета. |
| [MultiplyHue](#MultiplyHue) | Умножает оттенок цвета на значение параметра. |
| [SetSaturation](#SetSaturation) | Изменяет насыщенность (saturation) цвета на значение параметра. |
| [AddSaturation](#AddSaturation) | Добавляет значение параметра к насыщенности цвета. |
| [MultiplySaturation](#MultiplySaturation) | Умножает насыщенность цвета на значение параметра. |
| [SetLuminance](#SetLuminance) | Изменяет яркость (luminance) цвета на значение параметра. |
| [AddLuminance](#AddLuminance) | Добавляет значение параметра к яркости цвета. |
| [MultiplyLuminance](#MultiplyLuminance) | Умножает яркость цвета на значение параметра. |
| [SetRed](#SetRed) | Изменяет красный компонент цвета на значение параметра. |
| [AddRed](#AddRed) | Добавляет значение параметра к красному компоненту цвета. |
| [MultiplyRed](#MultiplyRed) | Умножает красный компонент на значение параметра. |
| [SetGreen](#SetGreen) | Изменяет зелёный компонент цвета на значение параметра. |
| [AddGreen](#AddGreen) | Добавляет значение параметра к зелёному компоненту цвета. |
| [MultiplyGreen](#MultiplyGreen) | Умножает зелёный компонент цвета на значение параметра. |
| [SetBlue](#SetBlue) | Изменяет синий компонент цвета на значение параметра. |
| [AddBlue](#AddBlue) | Добавляет значение параметра к синему компоненту цвета. |
| [MultiplyBlue](#MultiplyBlue) | Умножает синий компонент цвета на значение параметра. |
| [Gamma](#Gamma) | Гамма-коррекция. |
| [InverseGamma](#InverseGamma) | Обратная гамма-коррекция. |

### Tint {#Tint}
```
public static final int Tint
```

Тонирует цвет. Параметр находится в диапазоне от 0 (исходный цвет) до 1 (белый).

### Shade {#Shade}
```
public static final int Shade
```

Затемняет цвет. Параметр находится в диапазоне от 0 (исходный цвет) до 1 (чёрный).

### Complement {#Complement}
```
public static final int Complement
```

Изменяет цвет на RGB-комплементарный. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Изменяет цвет на инвертированный. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Изменяет цвет на серый с той же яркостью. Параметр игнорируется.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Определяет альфа-компонент цвета. Параметр находится в диапазоне от 0 (прозрачный) до 1 (непрозрачный).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Добавляет значение параметра к альфа-компоненту цвета. Параметр находится в диапазоне от -1 до 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Умножает альфа-компонент на значение параметра.

### SetHue {#SetHue}
```
public static final int SetHue
```

Изменяет оттенок (hue) цвета на значение параметра. Параметр находится в диапазоне от 0 до 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Добавляет значение параметра к оттенку цвета. Параметр находится в диапазоне от -360 до 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Умножает оттенок цвета на значение параметра.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Изменяет насыщенность (saturation) цвета на значение параметра. Параметр находится в диапазоне от 0 до 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Добавляет значение параметра к насыщенности цвета. Параметр находится в диапазоне от -1 до 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Умножает насыщенность цвета на значение параметра.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Изменяет яркость (luminance) цвета на значение параметра. Параметр находится в диапазоне от 0 до 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Добавляет значение параметра к яркости цвета. Параметр находится в диапазоне от -1 до 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Умножает яркость цвета на значение параметра.

### SetRed {#SetRed}
```
public static final int SetRed
```

Изменяет красный компонент цвета на значение параметра. Параметр находится в диапазоне от 0 до 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Добавляет значение параметра к красному компоненту цвета. Параметр находится в диапазоне от -1 до 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Умножает красный компонент на значение параметра.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Изменяет зелёный компонент цвета на значение параметра. Параметр находится в диапазоне от 0 до 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Добавляет значение параметра к зелёному компоненту цвета. Параметр находится в диапазоне от -1 до 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Умножает зелёный компонент цвета на значение параметра.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Изменяет синий компонент цвета на значение параметра. Параметр находится в диапазоне от 0 до 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Добавляет значение параметра к синему компоненту цвета. Параметр находится в диапазоне от -1 до 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Умножает синий компонент цвета на значение параметра.

### Gamma {#Gamma}
```
public static final int Gamma
```

Гамма-коррекция. Параметр игнорируется.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Обратная гамма-коррекция. Параметр игнорируется.