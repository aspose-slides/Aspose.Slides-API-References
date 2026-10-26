---
title: ColorTransformOperation
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يعرّف عملية تحويل اللون.
type: docs
url: /ar/com.aspose.slides/colortransformoperation/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

يعرّف عملية تحويل اللون.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Tint](#Tint) | يضيف صبغة إلى اللون. |
| [Shade](#Shade) | يضيف ظلًا إلى اللون. |
| [Complement](#Complement) | يُحوِّل اللون إلى لون مكمل بنظام RGB. |
| [Inverse](#Inverse) | يُحوِّل اللون إلى لون معكوس. |
| [Grayscale](#Grayscale) | يُحوِّل اللون إلى لون رمادي بنفس السطوع. |
| [SetAlpha](#SetAlpha) | يحدد مكوّن ألفا للون. |
| [AddAlpha](#AddAlpha) | يضيف قيمة المعامل إلى مكوّن ألفا للون. |
| [MultiplyAlpha](#MultiplyAlpha) | يضرب مكوّن ألفا في قيمة المعامل. |
| [SetHue](#SetHue) | يغيّر مكوّن الصيغة اللونية (Hue) للون إلى قيمة المعامل. |
| [AddHue](#AddHue) | يضيف قيمة المعامل إلى مكوّن الصيغة اللونية للون. |
| [MultiplyHue](#MultiplyHue) | يضرب مكوّن الصيغة اللونية في قيمة المعامل. |
| [SetSaturation](#SetSaturation) | يغيّر مكوّن التشبع للون إلى قيمة المعامل. |
| [AddSaturation](#AddSaturation) | يضيف قيمة المعامل إلى مكوّن التشبع للون. |
| [MultiplySaturation](#MultiplySaturation) | يضرب مكوّن التشبع في قيمة المعامل. |
| [SetLuminance](#SetLuminance) | يغيّر مكوّن الإضاءة للون إلى قيمة المعامل. |
| [AddLuminance](#AddLuminance) | يضيف قيمة المعامل إلى مكوّن الإضاءة للون. |
| [MultiplyLuminance](#MultiplyLuminance) | يضرب مكوّن الإضاءة في قيمة المعامل. |
| [SetRed](#SetRed) | يغيّر مكوّن الأحمر للون إلى قيمة المعامل. |
| [AddRed](#AddRed) | يضيف قيمة المعامل إلى مكوّن الأحمر للون. |
| [MultiplyRed](#MultiplyRed) | يضرب مكوّن الأحمر في المعامل. |
| [SetGreen](#SetGreen) | يغيّر مكوّن الأخضر للون إلى قيمة المعامل. |
| [AddGreen](#AddGreen) | يضيف المعامل إلى مكوّن الأخضر للون. |
| [MultiplyGreen](#MultiplyGreen) | يضرب مكوّن الأخضر في قيمة المعامل. |
| [SetBlue](#SetBlue) | يغيّر مكوّن الأزرق للون إلى قيمة المعامل. |
| [AddBlue](#AddBlue) | يضيف قيمة المعامل إلى مكوّن الأزرق للون. |
| [MultiplyBlue](#MultiplyBlue) | يضرب مكوّن الأزرق في قيمة المعامل. |
| [Gamma](#Gamma) | تصحيح غاما. |
| [InverseGamma](#InverseGamma) | تصحيح غاما عكسي. |
### Tint {#Tint}
```
public static final int Tint
```

يُصَبغ اللون. المعامل في النطاق بين 0 (اللون الأصلي) و 1 (الأبيض).

### Shade {#Shade}
```
public static final int Shade
```

يضفي ظلًا لللون. المعامل في النطاق بين 0 (اللون الأصلي) و 1 (الأسود).

### Complement {#Complement}
```
public static final int Complement
```

يُحوِّل اللون إلى لون مكمل بنظام RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

يُحوِّل اللون إلى لون معكوس. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

يُحوِّل اللون إلى لون رمادي بنفس السطوع. يتم تجاهل المعامل.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

يحدد مكوّن ألفا للون. المعامل في النطاق بين 0 (شفاف) و 1 (معتم).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

يضيف قيمة المعامل إلى مكوّن ألفا للون. المعامل في النطاق بين -1 و 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

يضرب مكوّن ألفا في قيمة المعامل.

### SetHue {#SetHue}
```
public static final int SetHue
```

يغيّر مكوّن الصيغة اللونية (Hue) للون إلى قيمة المعامل. المعامل في النطاق بين 0 و 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

يضيف قيمة المعامل إلى مكوّن الصيغة اللونية للون. المعامل في النطاق بين -360 و 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

يضرب مكوّن الصيغة اللونية في قيمة المعامل.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

يغيّر مكوّن التشبع للون إلى قيمة المعامل. المعامل في النطاق بين 0 و 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

يضيف قيمة المعامل إلى مكوّن التشبع للون. المعامل في النطاق بين -1 و 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

يضرب مكوّن التشبع في قيمة المعامل.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

يغيّر مكوّن الإضاءة للون إلى قيمة المعامل. المعامل في النطاق بين 0 و 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

يضيف قيمة المعامل إلى مكوّن الإضاءة للون. المعامل في النطاق بين -1 و 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

يضرب مكوّن الإضاءة في قيمة المعامل.

### SetRed {#SetRed}
```
public static final int SetRed
```

يغيّر مكوّن الأحمر للون إلى قيمة المعامل. المعامل في النطاق بين 0 و 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

يضيف قيمة المعامل إلى مكوّن الأحمر للون. المعامل في النطاق بين -1 و 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

يضرب مكوّن الأحمر في المعامل.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

يغيّر مكوّن الأخضر للون إلى قيمة المعامل. المعامل في النطاق بين 0 و 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

يضيف المعامل إلى مكوّن الأخضر للون. المعامل في النطاق بين -1 و 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

يضرب مكوّن الأخضر في قيمة المعامل.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

يغيّر مكوّن الأزرق للون إلى قيمة المعامل. المعامل في النطاق بين 0 و 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

يضيف قيمة المعامل إلى مكوّن الأزرق للون. المعامل في النطاق بين -1 و 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

يضرب مكوّن الأزرق في قيمة المعامل.

### Gamma {#Gamma}
```
public static final int Gamma
```

تصحيح غاما. يتم تجاهل المعامل.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

تصحيح غاما عكسي. يتم تجاهل المعامل.