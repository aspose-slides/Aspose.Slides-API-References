---
title: ColorTransformOperation
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: रंग ट्रांसफ़ॉर्म ऑपरेशन को परिभाषित करता है।
type: docs
url: /hi/com.aspose.slides/colortransformoperation/
---
**विरासत:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

रंग ट्रांसफ़ॉर्म ऑपरेशन को परिभाषित करता है।

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Tint](#Tint) | रंग को टिंट करता है। |
| [Shade](#Shade) | रंग को शेड करता है। |
| [Complement](#Complement) | रंग को RGB पूरक रंग में बदलता है। |
| [Inverse](#Inverse) | रंग को उलटे रंग में बदलता है। |
| [Grayscale](#Grayscale) | रंग को समान लाइटनेस वाले ग्रे रंग में बदलता है। |
| [SetAlpha](#SetAlpha) | रंग का अल्फा घटक परिभाषित करता है। |
| [AddAlpha](#AddAlpha) | रंग के अल्फा घटक में पैरामीटर का मान जोड़ता है। |
| [MultiplyAlpha](#MultiplyAlpha) | अल्फा घटक को पैरामीटर के मान से गुणा करता है। |
| [SetHue](#SetHue) | रंग के ह्यू घटक को पैरामीटर के मान में बदलता है। |
| [AddHue](#AddHue) | ह्यू घटक में पैरामीटर का मान जोड़ता है। |
| [MultiplyHue](#MultiplyHue) | ह्यू घटक को पैरामीटर के मान से गुणा करता है। |
| [SetSaturation](#SetSaturation) | रंग के सैचुरेशन घटक को पैरामीटर के मान में बदलता है। |
| [AddSaturation](#AddSaturation) | सैचुरेशन घटक में पैरामीटर का मान जोड़ता है। |
| [MultiplySaturation](#MultiplySaturation) | सैचुरेशन घटक को पैरामीटर के मान से गुणा करता है। |
| [SetLuminance](#SetLuminance) | रंग के ल्यूमिनेंस घटक को पैरामीटर के मान में बदलता है। |
| [AddLuminance](#AddLuminance) | ल्यूमिनेंस घटक में पैरामीटर का मान जोड़ता है। |
| [MultiplyLuminance](#MultiplyLuminance) | ल्यूमिनेंस घटक को पैरामीटर के मान से गुणा करता है। |
| [SetRed](#SetRed) | रंग के लाल घटक को पैरामीटर के मान में बदलता है। |
| [AddRed](#AddRed) | लाल घटक में पैरामीटर का मान जोड़ता है। |
| [MultiplyRed](#MultiplyRed) | लाल घटक को पैरामीटर से गुणा करता है। |
| [SetGreen](#SetGreen) | रंग के हरे घटक को पैरामीटर के मान में बदलता है। |
| [AddGreen](#AddGreen) | हरे घटक में पैरामीटर जोड़ता है। |
| [MultiplyGreen](#MultiplyGreen) | हरे घटक को पैरामीटर के मान से गुणा करता है। |
| [SetBlue](#SetBlue) | रंग के नीले घटक को पैरामीटर के मान में बदलता है। |
| [AddBlue](#AddBlue) | नीले घटक में पैरामीटर का मान जोड़ता है। |
| [MultiplyBlue](#MultiplyBlue) | नीले घटक को पैरामीटर के मान से गुणा करता है। |
| [Gamma](#Gamma) | गामा सुधार। |
| [InverseGamma](#InverseGamma) | उलटा गामा सुधार। |

### Tint {#Tint}
```
public static final int Tint
```

रंग को टिंट करता है। पैरामीटर 0 (मूल रंग) और 1 (सफ़ेद) के बीच सीमा में होता है।

### Shade {#Shade}
```
public static final int Shade
```

रंग को शेड करता है। पैरामीटर 0 (मूल रंग) और 1 (काला) के बीच सीमा में होता है।

### Complement {#Complement}
```
public static final int Complement
```

रंग को RGB पूरक रंग में बदलता है। m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

रंग को उलटे रंग में बदलता है। r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

रंग को समान लाइटनेस वाले ग्रे रंग में बदलता है। पैरामीटर को अनदेखा किया जाता है।

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

रंग का अल्फा घटक परिभाषित करता है। पैरामीटर 0 (पारदर्शी) और 1 (अस्पष्ट) के बीच सीमा में होता है।

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

रंग के अल्फा घटक में पैरामीटर का मान जोड़ता है। पैरामीटर -1 और 1 के बीच सीमा में होता है।

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

अल्फा घटक को पैरामीटर के मान से गुणा करता है।

### SetHue {#SetHue}
```
public static final int SetHue
```

रंग के ह्यू घटक को पैरामीटर के मान में बदलता है। पैरामीटर 0 और 360 के बीच सीमा में होता है।

### AddHue {#AddHue}
```
public static final int AddHue
```

ह्यू घटक में पैरामीटर का मान जोड़ता है। पैरामीटर -360 और 360 के बीच सीमा में होता है।

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

ह्यू घटक को पैरामीटर के मान से गुणा करता है।

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

रंग के सैचुरेशन घटक को पैरामीटर के मान में बदलता है। पैरामीटर 0 और 1 के बीच सीमा में होता है।

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

सैचुरेशन घटक में पैरामीटर का मान जोड़ता है। पैरामीटर -1 और 1 के बीच सीमा में होता है।

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

सैचुरेशन घटक को पैरामीटर के मान से गुणा करता है।

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

रंग के ल्यूमिनेंस घटक को पैरामीटर के मान में बदलता है। पैरामीटर 0 और 1 के बीच सीमा में होता है।

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

ल्यूमिनेंस घटक में पैरामीटर का मान जोड़ता है। पैरामीटर -1 और 1 के बीच सीमा में होता है।

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

ल्यूमिनेंस घटक को पैरामीटर के मान से गुणा करता है।

### SetRed {#SetRed}
```
public static final int SetRed
```

रंग के लाल घटक को पैरामीटर के मान में बदलता है। पैरामीटर 0 और 1 के बीच सीमा में होता है।

### AddRed {#AddRed}
```
public static final int AddRed
```

लाल घटक में पैरामीटर का मान जोड़ता है। पैरामीटर -1 और 1 के बीच सीमा में होता है।

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

लाल घटक को पैरामीटर से गुणा करता है।

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

रंग के हरे घटक को पैरामीटर के मान में बदलता है। पैरामीटर 0 और 1 के बीच सीमा में होता है।

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

हरे घटक में पैरामीटर जोड़ता है। पैरामीटर -1 और 1 के बीच सीमा में होता है।

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

हरे घटक को पैरामीटर के मान से गुणा करता है।

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

रंग के नीले घटक को पैरामीटर के मान में बदलता है। पैरामीटर 0 और 360 के बीच सीमा में होता है।

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

नीले घटक में पैरामीटर का मान जोड़ता है। पैरामीटर -1 और 1 के बीच सीमा में होता है।

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

नीले घटक को पैरामीटर के मान से गुणा करता है।

### Gamma {#Gamma}
```
public static final int Gamma
```

गामा सुधार। पैरामीटर को अनदेखा किया जाता है।

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

उलटा गामा सुधार। पैरामीटर को अनदेखा किया जाता है।