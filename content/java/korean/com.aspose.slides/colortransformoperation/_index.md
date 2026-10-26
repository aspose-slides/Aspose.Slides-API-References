---
title: ColorTransformOperation
second_title: Aspose.Slides for Java API 레퍼런스
description: 색 변환 작업을 정의합니다.
type: docs
url: /ko/com.aspose.slides/colortransformoperation/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

색 변환 작업을 정의합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Tint](#Tint) | 색을 색조합니다. |
| [Shade](#Shade) | 색을 음영 처리합니다. |
| [Complement](#Complement) | 색을 RGB 보색으로 변경합니다. |
| [Inverse](#Inverse) | 색을 반전된 색으로 변경합니다. |
| [Grayscale](#Grayscale) | 동일한 밝기의 회색으로 색을 변경합니다. |
| [SetAlpha](#SetAlpha) | 색의 알파 구성 요소를 정의합니다. |
| [AddAlpha](#AddAlpha) | 색의 알파 구성 요소에 매개변수 값을 추가합니다. |
| [MultiplyAlpha](#MultiplyAlpha) | 알파 구성 요소에 매개변수 값을 곱합니다. |
| [SetHue](#SetHue) | 색상의 색조 구성 요소를 매개변수 값으로 변경합니다. |
| [AddHue](#AddHue) | 색조 구성 요소에 매개변수 값을 추가합니다. |
| [MultiplyHue](#MultiplyHue) | 색조 구성 요소에 매개변수 값을 곱합니다. |
| [SetSaturation](#SetSaturation) | 색상의 채도 구성 요소를 매개변수 값으로 변경합니다. |
| [AddSaturation](#AddSaturation) | 채도 구성 요소에 매개변수 값을 추가합니다. |
| [MultiplySaturation](#MultiplySaturation) | 채도 구성 요소에 매개변수 값을 곱합니다. |
| [SetLuminance](#SetLuminance) | 색상의 명도 구성 요소를 매개변수 값으로 변경합니다. |
| [AddLuminance](#AddLuminance) | 명도 구성 요소에 매개변수 값을 추가합니다. |
| [MultiplyLuminance](#MultiplyLuminance) | 명도 구성 요소에 매개변수 값을 곱합니다. |
| [SetRed](#SetRed) | 색상의 빨간색 구성 요소를 매개변수 값으로 변경합니다. |
| [AddRed](#AddRed) | 빨간색 구성 요소에 매개변수 값을 추가합니다. |
| [MultiplyRed](#MultiplyRed) | 빨간색 구성 요소에 매개변수를 곱합니다. |
| [SetGreen](#SetGreen) | 색상의 녹색 구성 요소를 매개변수 값으로 변경합니다. |
| [AddGreen](#AddGreen) | 녹색 구성 요소에 매개변수를 추가합니다. |
| [MultiplyGreen](#MultiplyGreen) | 녹색 구성 요소에 매개변수 값을 곱합니다. |
| [SetBlue](#SetBlue) | 색상의 파란색 구성 요소를 매개변수 값으로 변경합니다. |
| [AddBlue](#AddBlue) | 파란색 구성 요소에 매개변수 값을 추가합니다. |
| [MultiplyBlue](#MultiplyBlue) | 파란색 구성 요소에 매개변수 값을 곱합니다. |
| [Gamma](#Gamma) | 감마 보정. |
| [InverseGamma](#InverseGamma) | 역 감마 보정. |
### Tint {#Tint}
```
public static final int Tint
```

색을 색조합니다. 매개변수는 0(원래 색)과 1(흰색) 사이의 범위입니다.

### Shade {#Shade}
```
public static final int Shade
```

색을 음영 처리합니다. 매개변수는 0(원래 색)과 1(검정) 사이의 범위입니다.

### Complement {#Complement}
```
public static final int Complement
```

색을 RGB 보색으로 변경합니다. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

색을 반전된 색으로 변경합니다. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

동일한 밝기의 회색으로 색을 변경합니다. 매개변수는 무시됩니다.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

색의 알파 구성 요소를 정의합니다. 매개변수는 0(투명)과 1(불투명) 사이의 범위입니다.

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

색의 알파 구성 요소에 매개변수 값을 추가합니다. 매개변수는 -1과 1 사이의 범위입니다.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

알파 구성 요소에 매개변수 값을 곱합니다.

### SetHue {#SetHue}
```
public static final int SetHue
```

색상의 색조 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 360 사이의 범위입니다.

### AddHue {#AddHue}
```
public static final int AddHue
```

색조 구성 요소에 매개변수 값을 추가합니다. 매개변수는 -360과 360 사이의 범위입니다.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

색조 구성 요소에 매개변수 값을 곱합니다.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

색상의 채도 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 1 사이의 범위입니다.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

채도 구성 요소에 매개변수 값을 추가합니다. 매개변수는 -1과 1 사이의 범위입니다.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

채도 구성 요소에 매개변수 값을 곱합니다.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

색상의 명도 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 1 사이의 범위입니다.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

명도 구성 요소에 매개변수 값을 추가합니다. 매개변수는 -1과 1 사이의 범위입니다.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

명도 구성 요소에 매개변수 값을 곱합니다.

### SetRed {#SetRed}
```
public static final int SetRed
```

색상의 빨간색 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 1 사이의 범위입니다.

### AddRed {#AddRed}
```
public static final int AddRed
```

빨간색 구성 요소에 매개변수 값을 추가합니다. 매개변수는 -1과 1 사이의 범위입니다.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

빨간색 구성 요소에 매개변수를 곱합니다.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

색상의 녹색 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 1 사이의 범위입니다.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

녹색 구성 요소에 매개변수를 추가합니다. 매개변수는 -1과 1 사이의 범위입니다.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

녹색 구성 요소에 매개변수 값을 곱합니다.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

색상의 파란색 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0와 360 사이의 범위입니다.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

파란색 구성 요소에 매개변수 값을 추가합니다. 매개변수는 -1과 1 사이의 범위입니다.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

파란색 구성 요소에 매개변수 값을 곱합니다.

### Gamma {#Gamma}
```
public static final int Gamma
```

감마 보정. 매개변수는 무시됩니다.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

역 감마 보정. 매개변수는 무시됩니다.