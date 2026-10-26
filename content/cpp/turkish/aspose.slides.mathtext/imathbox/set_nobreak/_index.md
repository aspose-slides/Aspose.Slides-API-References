---
title: set_NoBreak()
second_title: Aspose.Slides için C++ API Referansı
description: "Kesinti yok. Bu özellik nesne kutusundaki \"unbreakable\" özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatör içeren operatör emülatörleri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde kesintiler oluşabilir. Varsayılan: true"
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) yöntemi

Kesinti yok. Bu özellik, nesne kutusundaki \"unbreakable\" özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları gerçekleşemez. Bu, birden fazla ikili operatör içeren operatör emülatörleri için önemli olabilir. Bu eleman belirtilmediğinde, kutu içinde satır sonları oluşabilir. Default: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Açıklamalar

Örnek:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Bakınız

* Sınıf [IMathBox](../)
* İsim alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)