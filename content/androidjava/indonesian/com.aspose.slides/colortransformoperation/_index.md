---
title: ColorTransformOperation
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mendefinisikan operasi transformasi warna.
type: docs
url: /id/com.aspose.slides/colortransformoperation/
---
**Warisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Mendefinisikan operasi transformasi warna.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Tint](#Tint) | Mewarnai warna. |
| [Shade](#Shade) | Menggelapkan warna. |
| [Complement](#Complement) | Mengubah warna menjadi komplementer RGB. |
| [Inverse](#Inverse) | Mengubah warna menjadi warna terbalik. |
| [Grayscale](#Grayscale) | Mengubah warna menjadi abu-abu dengan kecerahan yang sama. |
| [SetAlpha](#SetAlpha) | Mendefinisikan komponen alfa warna. |
| [AddAlpha](#AddAlpha) | Menambahkan nilai parameter ke komponen alfa warna. |
| [MultiplyAlpha](#MultiplyAlpha) | Mengalikan komponen alfa dengan nilai parameter. |
| [SetHue](#SetHue) | Mengubah komponen hue warna menjadi nilai parameter. |
| [AddHue](#AddHue) | Menambahkan nilai parameter ke komponen hue warna. |
| [MultiplyHue](#MultiplyHue) | Mengalikan komponen hue dengan nilai parameter. |
| [SetSaturation](#SetSaturation) | Mengubah komponen saturasi warna menjadi nilai parameter. |
| [AddSaturation](#AddSaturation) | Menambahkan nilai parameter ke komponen saturasi warna. |
| [MultiplySaturation](#MultiplySaturation) | Mengalikan komponen saturasi dengan nilai parameter. |
| [SetLuminance](#SetLuminance) | Mengubah komponen luminansi warna menjadi nilai parameter. |
| [AddLuminance](#AddLuminance) | Menambahkan nilai parameter ke komponen luminansi warna. |
| [MultiplyLuminance](#MultiplyLuminance) | Mengalikan komponen luminansi dengan nilai parameter. |
| [SetRed](#SetRed) | Mengubah komponen merah warna menjadi nilai parameter. |
| [AddRed](#AddRed) | Menambahkan nilai parameter ke komponen merah warna. |
| [MultiplyRed](#MultiplyRed) | Mengalikan komponen merah dengan parameter. |
| [SetGreen](#SetGreen) | Mengubah komponen hijau warna menjadi nilai parameter. |
| [AddGreen](#AddGreen) | Menambahkan parameter ke komponen hijau warna. |
| [MultiplyGreen](#MultiplyGreen) | Mengalikan komponen hijau warna dengan nilai parameter. |
| [SetBlue](#SetBlue) | Mengubah komponen biru warna menjadi nilai parameter. |
| [AddBlue](#AddBlue) | Menambahkan nilai parameter ke komponen biru warna. |
| [MultiplyBlue](#MultiplyBlue) | Mengalikan komponen biru dengan nilai parameter. |
| [Gamma](#Gamma) | Koreksi gamma. |
| [InverseGamma](#InverseGamma) | Koreksi gamma invers. |
### Tint {#Tint}
```
public static final int Tint
```

Mewarnai warna. Parameter berada dalam rentang antara 0 (warna asli) dan 1 (putih).

### Shade {#Shade}
```
public static final int Shade
```

Menggelapkan warna. Parameter berada dalam rentang antara 0 (warna asli) dan 1 (hitam).

### Complement {#Complement}
```
public static final int Complement
```

Mengubah warna menjadi komplementer RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Mengubah warna menjadi warna terbalik. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Mengubah warna menjadi abu-abu dengan kecerahan yang sama. Parameter diabaikan.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Mendefinisikan komponen alfa warna. Parameter berada dalam rentang antara 0 (transparan) dan 1 (opaque).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Menambahkan nilai parameter ke komponen alfa warna. Parameter berada dalam rentang antara -1 dan 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Mengalikan komponen alfa dengan nilai parameter.

### SetHue {#SetHue}
```
public static final int SetHue
```

Mengubah komponen hue warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Menambahkan nilai parameter ke komponen hue warna. Parameter berada dalam rentang antara -360 dan 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Mengalikan komponen hue dengan nilai parameter.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Mengubah komponen saturasi warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Menambahkan nilai parameter ke komponen saturasi warna. Parameter berada dalam rentang antara -1 dan 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Mengalikan komponen saturasi dengan nilai parameter.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Mengubah komponen luminansi warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Menambahkan nilai parameter ke komponen luminansi warna. Parameter berada dalam rentang antara -1 dan 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Mengalikan komponen luminansi dengan nilai parameter.

### SetRed {#SetRed}
```
public static final int SetRed
```

Mengubah komponen merah warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Menambahkan nilai parameter ke komponen merah warna. Parameter berada dalam rentang antara -1 dan 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Mengalikan komponen merah dengan parameter.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Mengubah komponen hijau warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Menambahkan parameter ke komponen hijau warna. Parameter berada dalam rentang antara -1 dan 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Mengalikan komponen hijau warna dengan nilai parameter.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Mengubah komponen biru warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Menambahkan nilai parameter ke komponen biru warna. Parameter berada dalam rentang antara -1 dan 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Mengalikan komponen biru warna dengan nilai parameter.

### Gamma {#Gamma}
```
public static final int Gamma
```

Koreksi gamma. Parameter diabaikan.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Koreksi gamma invers. Parameter diabaikan.