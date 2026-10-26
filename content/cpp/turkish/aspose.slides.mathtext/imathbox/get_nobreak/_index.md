---
title: get_NoBreak()
second_title: Aspose.Slides for C++ API Referansı
description: "No break. Bu özellik, nesne kutusundaki \"unbreakable\" özelliğini belirtir. true olduğunda, kutu içinde satır sonları meydana gelmez. Bu, birden fazla ikili operatörden oluşan operatör emülatörleri için önemli olabilir. Bu öğe belirtilmezse, kutu içinde satır sonları meydana gelebilir. Varsayılan: true"
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() metod

No break. Bu özellik, nesne kutusundaki "unbreakable" özelliğini belirler. true olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör emülatörleri için önemli olabilir. Bu öğe belirtilmezse, kutu içinde satır sonları oluşabilir. Varsayılan: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Açıklamalar

Örnek: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Bkz

* Class [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)