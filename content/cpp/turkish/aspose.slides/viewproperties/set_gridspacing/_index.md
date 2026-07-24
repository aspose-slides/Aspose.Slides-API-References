---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API Referansı
description: Sunum belgesinin altındaki ızgara için kullanılacak ızgara aralığını nokta cinsinden ayarlar. float yazın.
type: docs
weight: 105
url: /tr/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) yöntemi

Sunum belgesinin altındaki ızgarada kullanılacak ızgara aralığını, nokta cinsinden ayarlar. **float** yazın.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Açıklamalar

Izgara aralığı değeri pozitif bir sayı olmalıdır. Tipik değer aralığı 1 mm (2.8349607 nokta) ile 2 inç (144 nokta) arasındadır.

Aşağıdaki örnek kod, PowerPoint sunumundaki ızgara aralığını nasıl değiştireceğinizi gösterir.

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## İlgili

* Sınıf [ViewProperties](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)