---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides için C++ API Referansı
description: Strikethrough Bottom-Left to Top-Right (varsayılan false'tur). border box'ın alt-sol köşesinden üst-sağ köşesine uzanan bir üstü çizili çapraz çizginin gizli ya da gösterili durumunu belirtir.
type: docs
weight: 170
url: /tr/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() metodu


Alt Sol'dan Sağ Üste Çapraz Çizgi (varsayılan false'tur). Kenarlık kutusunun alt-sol köşesinden üst-sağ köşesine uzanan bir üstü çizili (strikethrough) çapraz çizginin gizli ya da gösterili durumunu belirler.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
```

## Açıklamalar


Örnek: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## Diğer Bilgiler

* Sınıf [IMathBorderBox](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)