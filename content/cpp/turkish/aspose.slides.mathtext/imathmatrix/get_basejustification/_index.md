---
title: get_BaseJustification()
second_title: Aspose.Slides C++ API Referansı
description: "Çevre metne göre dikey hizalamayı belirtir. Olası değerler üst, alt ve orta. Varsayılan: Orta"
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() metodu


Çevre metne göre dikey hizalamayı belirtir. Olası değerler top, bottom ve Center. Varsayılan: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Ayrıca Bakınız

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Sınıf [IMathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)