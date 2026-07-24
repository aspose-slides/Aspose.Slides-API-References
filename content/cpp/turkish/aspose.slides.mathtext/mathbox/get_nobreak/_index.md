---
title: get_NoBreak()
second_title: Aspose.Slides için C++ API Referansı
description: "Kırılma Yok Bu özellik, nesne kutusundaki \"unbreakable\" özelliğini belirtir. true olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör emülatörleri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde satır sonları oluşabilir. Varsayılan: true"
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() method

Kırılma Yok Bu özellik, nesne kutusundaki \"unbreakable\" özelliğini belirtir. true olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör emülatörleri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde satır sonları oluşabilir. Varsayılan: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Açıklamalar

Örnek: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Ayrıca Bakınız

* Sınıf [MathBox](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)