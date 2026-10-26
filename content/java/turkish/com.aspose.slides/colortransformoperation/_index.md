---
title: ColorTransformOperation
second_title: Aspose.Slides için Java API Referansı
description: Renk dönüşüm işlemini tanımlar.
type: docs
url: /tr/com.aspose.slides/colortransformoperation/
---
**Kalıtım:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Renk dönüştürme işlemini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Tint](#Tint) | Rengi tonlandırır. |
| [Shade](#Shade) | Rengi gölgeler. |
| [Complement](#Complement) | Rengi bir RGB tamamlayıcı renge getirir. |
| [Inverse](#Inverse) | Rengi ters bir renk haline getirir. |
| [Grayscale](#Grayscale) | Rengi aynı aydınlıkta gri bir renge dönüştürür. |
| [SetAlpha](#SetAlpha) | Rengin alfa bileşenini tanımlar. |
| [AddAlpha](#AddAlpha) | Bir parametrenin değerini rengin alfa bileşenine ekler. |
| [MultiplyAlpha](#MultiplyAlpha) | Alfa bileşenini bir parametrenin değeriyle çarpar. |
| [SetHue](#SetHue) | Rengin ton bileşenini bir parametrenin değerine değiştirir. |
| [AddHue](#AddHue) | Parametrenin değerini rengin ton bileşenine ekler. |
| [MultiplyHue](#MultiplyHue) | Ton bileşenini bir parametrenin değeriyle çarpar. |
| [SetSaturation](#SetSaturation) | Rengin doygunluk bileşenini bir parametrenin değerine değiştirir. |
| [AddSaturation](#AddSaturation) | Parametrenin değerini rengin doygunluk bileşenine ekler. |
| [MultiplySaturation](#MultiplySaturation) | Doygunluk bileşenini bir parametrenin değeriyle çarpar. |
| [SetLuminance](#SetLuminance) | Rengin parlaklık bileşenini bir parametrenin değerine değiştirir. |
| [AddLuminance](#AddLuminance) | Parametrenin değerini rengin parlaklık bileşenine ekler. |
| [MultiplyLuminance](#MultiplyLuminance) | Parlaklık bileşenini bir parametrenin değeriyle çarpar. |
| [SetRed](#SetRed) | Rengin kırmızı bileşenini bir parametrenin değerine değiştirir. |
| [AddRed](#AddRed) | Parametrenin değerini rengin kırmızı bileşenine ekler. |
| [MultiplyRed](#MultiplyRed) | Kırmızı bileşeni bir parametreyle çarpar. |
| [SetGreen](#SetGreen) | Rengin yeşil bileşenini bir parametrenin değerine değiştirir. |
| [AddGreen](#AddGreen) | Parametreyi rengin yeşil bileşenine ekler. |
| [MultiplyGreen](#MultiplyGreen) | Yeşil bileşeni bir parametrenin değeriyle çarpar. |
| [SetBlue](#SetBlue) | Rengin mavi bileşenini bir parametrenin değerine değiştirir. |
| [AddBlue](#AddBlue) | Parametrenin değerini rengin mavi bileşenine ekler. |
| [MultiplyBlue](#MultiplyBlue) | Mavi bileşeni bir parametrenin değeriyle çarpar. |
| [Gamma](#Gamma) | Gamma düzeltmesi. |
| [InverseGamma](#InverseGamma) | Ters gamma düzeltmesi. |
### Tint {#Tint}
```
public static final int Tint
```

Rengi tonlandırır. Parametre 0 (orijinal renk) ile 1 (beyaz) arasında bir aralıktadır.

### Shade {#Shade}
```
public static final int Shade
```

Rengi gölgeler. Parametre 0 (orijinal renk) ile 1 (siyah) arasında bir aralıktadır.

### Complement {#Complement}
```
public static final int Complement
```

Rengi bir RGB tamamlayıcı renge değiştirir. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Rengi ters bir renge değiştirir. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Rengi aynı aydınlıkta gri bir renge değiştirir. Parametre yok sayılır.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Rengin alfa bileşenini tanımlar. Parametre 0 (şeffaf) ile 1 (opak) arasında bir aralıktadır.

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Bir parametrenin değerini rengin alfa bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Alfa bileşenini bir parametrenin değeriyle çarpar.

### SetHue {#SetHue}
```
public static final int SetHue
```

Rengin ton bileşenini bir parametrenin değerine değiştirir. Parametre 0 ile 360 arasında bir aralıktadır.

### AddHue {#AddHue}
```
public static final int AddHue
```

Parametrenin değerini rengin ton bileşenine ekler. Parametre -360 ile 360 arasında bir aralıktadır.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Ton bileşenini bir parametrenin değeriyle çarpar.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Rengin doygunluk bileşenini bir parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Parametrenin değerini rengin doygunluk bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Doygunluk bileşenini bir parametrenin değeriyle çarpar.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Rengin parlaklık bileşenini bir parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Parametrenin değerini rengin parlaklık bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Parlaklık bileşenini bir parametrenin değeriyle çarpar.

### SetRed {#SetRed}
```
public static final int SetRed
```

Rengin kırmızı bileşenini bir parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır.

### AddRed {#AddRed}
```
public static final int AddRed
```

Parametrenin değerini rengin kırmızı bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Kırmızı bileşeni bir parametreyle çarpar.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Rengin yeşil bileşenini bir parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Parametreyi rengin yeşil bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Yeşil bileşeni bir parametrenin değeriyle çarpar.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Rengin mavi bileşenini bir parametrenin değerine değiştirir. Parametre 0 ile 360 arasında bir aralıktadır.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Parametrenin değerini rengin mavi bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Mavi bileşeni bir parametrenin değeriyle çarpar.

### Gamma {#Gamma}
```
public static final int Gamma
```

Gamma düzeltmesi. Parametre yok sayılır.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Ters gamma düzeltmesi. Parametre yok sayılır.