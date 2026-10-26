---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enumerasyonu

Renk dönüşüm işlemini tanımlar.

ColorTransformOperation türü aşağıdaki üyeleri sunar:

## Alanlar

| Alan | Açıklama |
| :- | :- |
| TINT | Rengi tonlandırır. Parametre 0 (orijinal renk) ile 1 (beyaz) arasında bir aralıktadır. |
| SHADE | Rengi gölgeler. Parametre 0 (orijinal renk) ile 1 (siyah) arasında bir aralıktadır. |
| COMPLEMENT | Rengi RGB tamamlayıcı bir renge değiştirir.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Rengi ters bir renge değiştirir.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Rengi aynı parlaklıkta gri bir renge değiştirir. Parametre yoksayılır. |
| SET_ALPHA | Rengin alfa bileşenini tanımlar. Parametre 0 (şeffaf) ile 1 (opak) arasında bir aralıktadır. |
| ADD_ALPHA | Parametrenin değerini rengin alfa bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MULTIPLY_ALPHA | Alfa bileşenini parametrenin değeriyle çarpar. |
| SET_HUE | Rengin ton bileşenini parametrenin değerine değiştirir. Parametre 0 ile 360 arasında bir aralıktadır. |
| ADD_HUE | Parametrenin değerini rengin ton bileşenine ekler. Parametre -360 ile 360 arasında bir aralıktadır. |
| MULTIPLY_HUE | Ton bileşenini parametrenin değeriyle çarpar. |
| SET_SATURATION | Rengin doygunluk bileşenini parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır. |
| ADD_SATURATION | Parametrenin değerini rengin doygunluk bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MULTIPLY_SATURATION | Doygunluk bileşenini parametrenin değeriyle çarpar. |
| SET_LUMINANCE | Rengin parlaklık bileşenini parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır. |
| ADD_LUMINANCE | Parametrenin değerini rengin parlaklık bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MULTIPLY_LUMINANCE | Parlaklık bileşenini parametrenin değeriyle çarpar. |
| SET_RED | Rengin kırmızı bileşenini parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır. |
| ADD_RED | Parametrenin değerini rengin kırmızı bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MULTIPLY_RED | Kırmızı bileşenini parametreyle çarpar. |
| SET_GREEN | Rengin yeşil bileşenini parametrenin değerine değiştirir. Parametre 0 ile 1 arasında bir aralıktadır. |
| ADD_GREEN | Parametrenin değerini rengin yeşil bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MULTIPLY_GREEN | Yeşil bileşenini parametrenin değeriyle çarpar. |
| SET_BLUE | Rengin mavi bileşenini parametrenin değerine değiştirir. Parametre 0 ile 360 arasında bir aralıktadır. |
| ADD_BLUE | Parametrenin değerini rengin mavi bileşenine ekler. Parametre -1 ile 1 arasında bir aralıktadır. |
| MULTIPLY_BLUE | Mavi bileşenini parametrenin değeriyle çarpar. |
| GAMMA | Gamma düzeltmesi. Parametre yoksayılır. |
| INVERSE_GAMMA | Ters gamma düzeltmesi. Parametre yoksayılır. |

### Ayrıca bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)