---
title: ColorTransformOperation
second_title: Aspose.Slides for C++ API Referansı
description: Renk dönüşüm işlemini tanımlar.
type: docs
weight: 5747
url: /tr/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Renk dönüşüm işlemini tanımlar.

```cpp
enum class ColorTransformOperation
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Tint | 0 | Rengi tonu verir. Parametre 0 (orijinal renk) ile 1 (beyaz) arasında bir aralıktadır. |
| Shade | 1 | Rengi gölgelendirir. Parametre 0 (orijinal renk) ile 1 (siyah) arasında bir aralıktadır. |
| Complement | 2 | Rengi RGB tamamlayıcı bir renge değiştirir. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Rengi tersine çevrilmiş bir renge değiştirir. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Rengi aynı parlaklığa sahip gri bir renge değiştirir. Parametre yok sayılır. |
| SetAlpha | 5 | Rengin alfa bileşenini tanımlar. Parametre 0 (şeffaf) ile 1 (opak) arasında bir aralıktadır. |
| AddAlpha | 6 | Parametrenin değerini rengin alfa bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MultiplyAlpha | 7 | Alfa bileşenini parametrenin değeriyle çarpar. |
| SetHue | 8 | Rengin ton bileşenini parametrenin değerine değiştirir. Parametre 0 ile 360 arasında bir aralıktadır. |
| AddHue | 9 | Parametrenin değerini rengin ton bileşenine ekler. Parametre -360 ile 360 arasında bir aralıktadır. |
| MultiplyHue | 10 | Ton bileşenini parametrenin değeriyle çarpar. |
| SetSaturation | 11 | Rengin doyma bileşenini parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır. |
| AddSaturation | 12 | Parametrenin değerini rengin doygunluk bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MultiplySaturation | 13 | Doyma bileşenini parametrenin değeriyle çarpar. |
| SetLuminance | 14 | Rengin parlaklık bileşenini parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır. |
| AddLuminance | 15 | Parametrenin değerini rengin parlaklık bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MultiplyLuminance | 16 | Parlaklık bileşenini parametrenin değeriyle çarpar. |
| SetRed | 17 | Rengin kırmızı bileşenini parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır. |
| AddRed | 18 | Parametrenin değerini rengin kırmızı bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MultiplyRed | 19 | Kırmızı bileşeni bir parametreyle çarpar. |
| SetGreen | 20 | Rengin yeşil bileşenini parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır. |
| AddGreen | 21 | Parametreyi rengin yeşil bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MultiplyGreen | 22 | Yeşil bileşeni parametrenin değeriyle çarpar. |
| SetBlue | 23 | Rengin mavi bileşenini parametrenin değerine değiştirir. Parametre 0 ile 360 arasında bir aralıktadır. |
| AddBlue | 24 | Parametrenin değerini rengin mavi bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MultiplyBlue | 25 | Mavi bileşeni parametrenin değeriyle çarpar. |
| Gamma | 26 | Gama düzeltmesi. Parametre yok sayılır. |
| InverseGamma | 27 | Ters gama düzeltmesi. Parametre yok sayılır. |

## İlgili

* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)