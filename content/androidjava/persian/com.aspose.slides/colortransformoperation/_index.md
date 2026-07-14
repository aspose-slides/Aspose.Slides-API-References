---
title: ColorTransformOperation
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: عملیات تبدیل رنگ را تعریف می‌کند.
type: docs
url: /fa/com.aspose.slides/colortransformoperation/
---
**ارث بری:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum  
```
public final class ColorTransformOperation extends System.Enum
```

عملیات تبدیل رنگ را تعریف می‌کند.  
## فیلدها

| فیلد | شرح |
| --- | --- |
| [Tint](#Tint) | رنگ را روشن می‌کند. |
| [Shade](#Shade) | رنگ را تیره می‌کند. |
| [Complement](#Complement) | رنگ را به یک رنگ مکمل RGB تغییر می‌دهد. |
| [Inverse](#Inverse) | رنگ را به یک رنگ معکوس تغییر می‌دهد. |
| [Grayscale](#Grayscale) | رنگ را به یک رنگ خاکستری با روشنایی یکسان تغییر می‌دهد. |
| [SetAlpha](#SetAlpha) | یک مؤلفهٔ آلفا برای رنگ تعریف می‌کند. |
| [AddAlpha](#AddAlpha) | مقدار پارامتر را به مؤلفهٔ آلفای رنگ اضافه می‌کند. |
| [MultiplyAlpha](#MultiplyAlpha) | مؤلفهٔ آلفا را در مقدار پارامتر ضرب می‌کند. |
| [SetHue](#SetHue) | مؤلفهٔ هیو رنگ را به مقدار پارامتر تغییر می‌دهد. |
| [AddHue](#AddHue) | مقدار پارامتر را به مؤلفهٔ هیو رنگ اضافه می‌کند. |
| [MultiplyHue](#MultiplyHue) | مؤلفهٔ هیو را در مقدار پارامتر ضرب می‌کند. |
| [SetSaturation](#SetSaturation) | مؤلفهٔ اشباع رنگ را به مقدار پارامتر تغییر می‌دهد. |
| [AddSaturation](#AddSaturation) | مقدار پارامتر را به مؤلفهٔ اشباع رنگ اضافه می‌کند. |
| [MultiplySaturation](#MultiplySaturation) | مؤلفهٔ اشباع را در مقدار پارامتر ضرب می‌کند. |
| [SetLuminance](#SetLuminance) | مؤلفهٔ روشنایی رنگ را به مقدار پارامتر تغییر می‌دهد. |
| [AddLuminance](#AddLuminance) | مقدار پارامتر را به مؤلفهٔ روشنایی رنگ اضافه می‌کند. |
| [MultiplyLuminance](#MultiplyLuminance) | مؤلفهٔ روشنایی را در مقدار پارامتر ضرب می‌کند. |
| [SetRed](#SetRed) | مؤلفهٔ قرمز رنگ را به مقدار پارامتر تغییر می‌دهد. |
| [AddRed](#AddRed) | مقدار پارامتر را به مؤلفهٔ قرمز رنگ اضافه می‌کند. |
| [MultiplyRed](#MultiplyRed) | مؤلفهٔ قرمز را در مقدار پارامتر ضرب می‌کند. |
| [SetGreen](#SetGreen) | مؤلفهٔ سبز رنگ را به مقدار پارامتر تغییر می‌دهد. |
| [AddGreen](#AddGreen) | مقدار پارامتر را به مؤلفهٔ سبز رنگ اضافه می‌کند. |
| [MultiplyGreen](#MultiplyGreen) | مؤلفهٔ سبز را در مقدار پارامتر ضرب می‌کند. |
| [SetBlue](#SetBlue) | مؤلفهٔ آبی رنگ را به مقدار پارامتر تغییر می‌دهد. |
| [AddBlue](#AddBlue) | مقدار پارامتر را به مؤلفهٔ آبی رنگ اضافه می‌کند. |
| [MultiplyBlue](#MultiplyBlue) | مؤلفهٔ آبی را در مقدار پارامتر ضرب می‌کند. |
| [Gamma](#Gamma) | تصحیح گاما. |
| [InverseGamma](#InverseGamma) | تصحیح گاما معکوس. |
### Tint {#Tint}
```
public static final int Tint
```

رنگ را روشن می‌کند. پارامتر در بازهٔ بین 0 (رنگ اصلی) و 1 (سفید) است.

### Shade {#Shade}
```
public static final int Shade
```

رنگ را تیره می‌کند. پارامتر در بازهٔ بین 0 (رنگ اصلی) و 1 (سیاه) است.

### Complement {#Complement}
```
public static final int Complement
```

رنگ را به یک رنگ مکمل RGB تغییر می‌دهد. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

رنگ را به یک رنگ معکوس تغییر می‌دهد. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

رنگ را به یک رنگ خاکستری با روشنایی یکسان تغییر می‌دهد. پارامتر نادیده گرفته می‌شود.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

یک مؤلفهٔ آلفا برای رنگ تعریف می‌کند. پارامتر در بازهٔ بین 0 (شفاف) و 1 (کدر) است.

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

مقدار پارامتر را به مؤلفهٔ آلفای رنگ اضافه می‌کند. پارامتر در بازهٔ بین -1 و 1 است.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

مؤلفهٔ آلفا را در مقدار پارامتر ضرب می‌کند.

### SetHue {#SetHue}
```
public static final int SetHue
```

مؤلفهٔ هیو رنگ را به مقدار پارامتر تغییر می‌دهد. پارامتر در بازهٔ بین 0 و 360 است.

### AddHue {#AddHue}
```
public static final int AddHue
```

مقدار پارامتر را به مؤلفهٔ هیو رنگ اضافه می‌کند. پارامتر در بازهٔ بین -360 و 360 است.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

مؤلفهٔ هیو را در مقدار پارامتر ضرب می‌کند.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

مؤلفهٔ اشباع رنگ را به مقدار پارامتر تغییر می‌دهد. پارامتر در بازهٔ بین 0 و 1 است.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

مقدار پارامتر را به مؤلفهٔ اشباع رنگ اضافه می‌کند. پارامتر در بازهٔ بین -1 و 1 است.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

مؤلفهٔ اشباع را در مقدار پارامتر ضرب می‌کند.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

مؤلفهٔ روشنایی رنگ را به مقدار پارامتر تغییر می‌دهد. پارامتر در بازهٔ بین 0 و 1 است.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

مقدار پارامتر را به مؤلفهٔ روشنایی رنگ اضافه می‌کند. پارامتر در بازهٔ بین -1 و 1 است.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

مؤلفهٔ روشنایی را در مقدار پارامتر ضرب می‌کند.

### SetRed {#SetRed}
```
public static final int SetRed
```

مؤلفهٔ قرمز رنگ را به مقدار پارامتر تغییر می‌دهد. پارامتر در بازهٔ بین 0 و 1 است.

### AddRed {#AddRed}
```
public static final int AddRed
```

مقدار پارامتر را به مؤلفهٔ قرمز رنگ اضافه می‌کند. پارامتر در بازهٔ بین -1 و 1 است.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

مؤلفهٔ قرمز را در مقدار پارامتر ضرب می‌کند.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

مؤلفهٔ سبز رنگ را به مقدار پارامتر تغییر می‌دهد. پارامتر در بازهٔ بین 0 و 1 است.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

مقدار پارامتر را به مؤلفهٔ سبز رنگ اضافه می‌کند. پارامتر در بازهٔ بین -1 و 1 است.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

مؤلفهٔ سبز را در مقدار پارامتر ضرب می‌کند.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

مؤلفهٔ آبی رنگ را به مقدار پارامتر تغییر می‌دهد. پارامتر در بازهٔ بین 0 و 360 است.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

مقدار پارامتر را به مؤلفهٔ آبی رنگ اضافه می‌کند. پارامتر در بازهٔ بین -1 و 1 است.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

مؤلفهٔ آبی را در مقدار پارامتر ضرب می‌کند.

### Gamma {#Gamma}
```
public static final int Gamma
```

تصحیح گاما. پارامتر نادیده گرفته می‌شود.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

تصحیح گاما معکوس. پارامتر نادیده گرفته می‌شود.