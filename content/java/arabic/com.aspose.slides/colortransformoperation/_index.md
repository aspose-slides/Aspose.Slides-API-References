---
title: ColorTransformOperation
second_title: مرجع Aspose.Slides لواجهة برمجة تطبيقات جافا
description: يعرّف عملية تحويل اللون.
type: docs
url: /ar/com.aspose.slides/colortransformoperation/
---
**الوراثة:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

يعرف عملية تحويل اللون.  
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Tint](#Tint) | يضيف صبغة إلى اللون. |
| [Shade](#Shade) | يظلل اللون. |
| [Complement](#Complement) | يغيّر اللون إلى اللون التكميلي بنظام RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| [Inverse](#Inverse) | يغيّر اللون إلى لون معكوس. r = 1 - r; g = 1 - g; b = 1 - b; |
| [Grayscale](#Grayscale) | يغيّر اللون إلى اللون الرمادي بنفس الإضاءة. المتغيّر مُهمل. |
| [SetAlpha](#SetAlpha) | يحدد مكوّن ألفا للون. |
| [AddAlpha](#AddAlpha) | يضيف قيمة المتغيّر إلى مكوّن ألفا للون. |
| [MultiplyAlpha](#MultiplyAlpha) | يضرب مكوّن ألفا في قيمة المتغيّر. |
| [SetHue](#SetHue) | يغيّر مكوّن اللون (Hue) للون إلى قيمة المتغيّر. |
| [AddHue](#AddHue) | يضيف قيمة المتغيّر إلى مكوّن اللون (Hue) للون. |
| [MultiplyHue](#MultiplyHue) | يضرب مكوّن اللون (Hue) في قيمة المتغيّر. |
| [SetSaturation](#SetSaturation) | يغيّر مكوّن التشبع للون إلى قيمة المتغيّر. |
| [AddSaturation](#AddSaturation) | يضيف قيمة المتغيّر إلى مكوّن التشبع للون. |
| [MultiplySaturation](#MultiplySaturation) | يضرب مكوّن التشبع في قيمة المتغيّر. |
| [SetLuminance](#SetLuminance) | يغيّر مكوّن الإضاءة للون إلى قيمة المتغيّر. |
| [AddLuminance](#AddLuminance) | يضيف قيمة المتغيّر إلى مكوّن الإضاءة للون. |
| [MultiplyLuminance](#MultiplyLuminance) | يضرب مكوّن الإضاءة في قيمة المتغيّر. |
| [SetRed](#SetRed) | يغيّر مكوّن الأحمر للون إلى قيمة المتغيّر. |
| [AddRed](#AddRed) | يضيف قيمة المتغيّر إلى مكوّن الأحمر للون. |
| [MultiplyRed](#MultiplyRed) | يضرب مكوّن الأحمر في المتغيّر. |
| [SetGreen](#SetGreen) | يغيّر مكوّن الأخضر للون إلى قيمة المتغيّر. |
| [AddGreen](#AddGreen) | يضيف المتغيّر إلى مكوّن الأخضر للون. |
| [MultiplyGreen](#MultiplyGreen) | يضرب مكوّن الأخضر في قيمة المتغيّر. |
| [SetBlue](#SetBlue) | يغيّر مكوّن الأزرق للون إلى قيمة المتغيّر. |
| [AddBlue](#AddBlue) | يضيف قيمة المتغيّر إلى مكوّن الأزرق للون. |
| [MultiplyBlue](#MultiplyBlue) | يضرب مكوّن الأزرق في قيمة المتغيّر. |
| [Gamma](#Gamma) | تصحيح جاما. |
| [InverseGamma](#InverseGamma) | تصحيح جاما عكسي. |
### تلوين {#Tint}
```
public static final int Tint
```

يضيف صبغة إلى اللون. المتغيّر في النطاق بين 0 (اللون الأصلي) و 1 (الأبيض).

### تظليل {#Shade}
```
public static final int Shade
```

يظلل اللون. المتغيّر في النطاق بين 0 (اللون الأصلي) و 1 (الأسود).

### مكمل {#Complement}
```
public static final int Complement
```

يغيّر اللون إلى اللون التكميلي بنظام RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### عكسي {#Inverse}
```
public static final int Inverse
```

يغيّر اللون إلى لون معكوس. r = 1 - r; g = 1 - g; b = 1 - b;

### تدرج رمادي {#Grayscale}
```
public static final int Grayscale
```

يغيّر اللون إلى اللون الرمادي بنفس الإضاءة. المتغيّر مُهمل.

### تعيين ألفا {#SetAlpha}
```
public static final int SetAlpha
```

يحدد مكوّن ألفا للون. المتغيّر في النطاق بين 0 (شفاف) و 1 (معتم).

### إضافة ألفا {#AddAlpha}
```
public static final int AddAlpha
```

يضيف قيمة المتغيّر إلى مكوّن ألفا للون. المتغيّر في النطاق بين -1 و 1.

### ضرب ألفا {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

يضرب مكوّن ألفا في قيمة المتغيّر.

### تعيين لون (Hue) {#SetHue}
```
public static final int SetHue
```

يغيّر مكوّن اللون (Hue) للون إلى قيمة المتغيّر. المتغيّر في النطاق بين 0 و 360.

### إضافة لون (Hue) {#AddHue}
```
public static final int AddHue
```

يضيف قيمة المتغيّر إلى مكوّن اللون (Hue) للون. المتغيّر في النطاق بين -360 و 360.

### ضرب لون (Hue) {#MultiplyHue}
```
public static final int MultiplyHue
```

يضرب مكوّن اللون (Hue) في قيمة المتغيّر.

### تعيين التشبع {#SetSaturation}
```
public static final int SetSaturation
```

يغيّر مكوّن التشبع للون إلى قيمة المتغيّر. المتغيّر في النطاق بين 0 و 1.

### إضافة التشبع {#AddSaturation}
```
public static final int AddSaturation
```

يضيف قيمة المتغيّر إلى مكوّن التشبع للون. المتغيّر في النطاق بين -1 و 1.

### ضرب التشبع {#MultiplySaturation}
```
public static final int MultiplySaturation
```

يضرب مكوّن التشبع في قيمة المتغيّر.

### تعيين الإضاءة {#SetLuminance}
```
public static final int SetLuminance
```

يغيّر مكوّن الإضاءة للون إلى قيمة المتغيّر. المتغيّر في النطاق بين 0 و 1.

### إضافة الإضاءة {#AddLuminance}
```
public static final int AddLuminance
```

يضيف قيمة المتغيّر إلى مكوّن الإضاءة للون. المتغيّر في النطاق بين -1 و 1.

### ضرب الإضاءة {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

يضرب مكوّن الإضاءة في قيمة المتغيّر.

### تعيين الأحمر {#SetRed}
```
public static final int SetRed
```

يغيّر مكوّن الأحمر للون إلى قيمة المتغيّر. المتغيّر في النطاق بين 0 و 1.

### إضافة الأحمر {#AddRed}
```
public static final int AddRed
```

يضيف قيمة المتغيّر إلى مكوّن الأحمر للون. المتغيّر في النطاق بين -1 و 1.

### ضرب الأحمر {#MultiplyRed}
```
public static final int MultiplyRed
```

يضرب مكوّن الأحمر في المتغيّر.

### تعيين الأخضر {#SetGreen}
```
public static final int SetGreen
```

يغيّر مكوّن الأخضر للون إلى قيمة المتغيّر. المتغيّر في النطاق بين 0 و 1.

### إضافة الأخضر {#AddGreen}
```
public static final int AddGreen
```

يضيف المتغيّر إلى مكوّن الأخضر للون. المتغيّر في النطاق بين -1 و 1.

### ضرب الأخضر {#MultiplyGreen}
```
public static final int MultiplyGreen
```

يضرب مكوّن الأخضر في قيمة المتغيّر.

### تعيين الأزرق {#SetBlue}
```
public static final int SetBlue
```

يغيّر مكوّن الأزرق للون إلى قيمة المتغيّر. المتغيّر في النطاق بين 0 و 360.

### إضافة الأزرق {#AddBlue}
```
public static final int AddBlue
```

يضيف قيمة المتغيّر إلى مكوّن الأزرق للون. المتغيّر في النطاق بين -1 و 1.

### ضرب الأزرق {#MultiplyBlue}
```
public static final int MultiplyBlue
```

يضرب مكوّن الأزرق في قيمة المتغيّر.

### جاما {#Gamma}
```
public static final int Gamma
```

تصحيح جاما. المتغيّر مُهمل.

### جاما عكسي {#InverseGamma}
```
public static final int InverseGamma
```

تصحيح جاما عكسي. المتغيّر مُهمل.