---
title: ColorTransformOperation
second_title: Aspose.Slides for Java API リファレンス
description: 色変換操作を定義します。
type: docs
url: /ja/com.aspose.slides/colortransformoperation/
---
**継承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

色変換操作を定義します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Tint](#Tint) | 色をティントします。 |
| [Shade](#Shade) | 色をシェードします。 |
| [Complement](#Complement) | 色をRGBの補色に変更します。 |
| [Inverse](#Inverse) | 色を反転色に変更します。 |
| [Grayscale](#Grayscale) | 色を同じ明度のグレーに変更します。 |
| [SetAlpha](#SetAlpha) | 色のアルファ成分を定義します。 |
| [AddAlpha](#AddAlpha) | パラメーターの値を色のアルファ成分に加算します。 |
| [MultiplyAlpha](#MultiplyAlpha) | アルファ成分をパラメーターの値で乗算します。 |
| [SetHue](#SetHue) | 色相成分をパラメーターの値に変更します。 |
| [AddHue](#AddHue) | パラメーターの値を色相成分に加算します。 |
| [MultiplyHue](#MultiplyHue) | 色相成分をパラメーターの値で乗算します。 |
| [SetSaturation](#SetSaturation) | 彩度成分をパラメーターの値に変更します。 |
| [AddSaturation](#AddSaturation) | パラメーターの値を彩度成分に加算します。 |
| [MultiplySaturation](#MultiplySaturation) | 彩度成分をパラメーターの値で乗算します。 |
| [SetLuminance](#SetLuminance) | 明度成分をパラメーターの値に変更します。 |
| [AddLuminance](#AddLuminance) | パラメーターの値を明度成分に加算します。 |
| [MultiplyLuminance](#MultiplyLuminance) | 明度成分をパラメーターの値で乗算します。 |
| [SetRed](#SetRed) | 赤成分をパラメーターの値に変更します。 |
| [AddRed](#AddRed) | パラメーターの値を赤成分に加算します。 |
| [MultiplyRed](#MultiplyRed) | 赤成分をパラメーターで乗算します。 |
| [SetGreen](#SetGreen) | 緑成分をパラメーターの値に変更します。 |
| [AddGreen](#AddGreen) | パラメーターの値を緑成分に加算します。 |
| [MultiplyGreen](#MultiplyGreen) | 緑成分をパラメーターの値で乗算します。 |
| [SetBlue](#SetBlue) | 青成分をパラメーターの値に変更します。 |
| [AddBlue](#AddBlue) | パラメーターの値を青成分に加算します。 |
| [MultiplyBlue](#MultiplyBlue) | 青成分をパラメーターの値で乗算します。 |
| [Gamma](#Gamma) | ガンマ補正。 |
| [InverseGamma](#InverseGamma) | 逆ガンマ補正。 |

### Tint {#Tint}
```
public static final int Tint
```

色をティントします。パラメーターは 0（元の色）から 1（白）までの範囲です。

### Shade {#Shade}
```
public static final int Shade
```

色をシェードします。パラメーターは 0（元の色）から 1（黒）までの範囲です。

### Complement {#Complement}
```
public static final int Complement
```

色をRGBの補色に変更します。m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

色を反転色に変更します。r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

色を同じ明度のグレーに変更します。パラメーターは無視されます。

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

色のアルファ成分を定義します。パラメーターは 0（透明）から 1（不透明）までの範囲です。

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

パラメーターの値を色のアルファ成分に加算します。パラメーターは -1 から 1 の範囲です。

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

アルファ成分をパラメーターの値で乗算します。

### SetHue {#SetHue}
```
public static final int SetHue
```

色相成分をパラメーターの値に変更します。パラメーターは 0 から 360 の範囲です。

### AddHue {#AddHue}
```
public static final int AddHue
```

パラメーターの値を色相成分に加算します。パラメーターは -360 から 360 の範囲です。

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

色相成分をパラメーターの値で乗算します。

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

彩度成分をパラメーターの値に変更します。パラメーターは 0 から 1 の範囲です。

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

パラメーターの値を彩度成分に加算します。パラメーターは -1 から 1 の範囲です。

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

彩度成分をパラメーターの値で乗算します。

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

明度成分をパラメーターの値に変更します。パラメーターは 0 から 1 の範囲です。

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

パラメーターの値を明度成分に加算します。パラメーターは -1 から 1 の範囲です。

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

明度成分をパラメーターの値で乗算します。

### SetRed {#SetRed}
```
public static final int SetRed
```

赤成分をパラメーターの値に変更します。パラメーターは 0 から 1 の範囲です。

### AddRed {#AddRed}
```
public static final int AddRed
```

パラメーターの値を赤成分に加算します。パラメーターは -1 から 1 の範囲です。

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

赤成分をパラメーターで乗算します。

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

緑成分をパラメーターの値に変更します。パラメーターは 0 から 1 の範囲です。

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

パラメーターの値を緑成分に加算します。パラメーターは -1 から 1 の範囲です。

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

緑成分をパラメーターの値で乗算します。

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

青成分をパラメーターの値に変更します。パラメーターは 0 から 360 の範囲です。

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

パラメーターの値を青成分に加算します。パラメーターは -1 から 1 の範囲です。

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

青成分をパラメーターの値で乗算します。

### Gamma {#Gamma}
```
public static final int Gamma
```

ガンマ補正。パラメーターは無視されます。

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

逆ガンマ補正。パラメーターは無視されます。