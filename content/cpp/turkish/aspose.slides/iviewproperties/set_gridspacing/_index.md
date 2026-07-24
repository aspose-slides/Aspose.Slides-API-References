---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API Referansı
description: Sunum belgesinin altındaki ızgara için kullanılacak ızgara aralığını nokta cinsinden ayarlar. Float olarak yazın.
type: docs
weight: 105
url: /tr/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) metodu

Sunum belgesinin altındaki ızgara için kullanılacak ızgara aralığını nokta cinsinden ayarlar. **float** olarak yazın.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Açıklamalar

Izgara aralığı değeri pozitif bir sayı olmalıdır. Tipik değer aralığı 1 mm (2.8349607 nokta) ile 2 inç (144 nokta) arasındadır.  

Aşağıdaki örnek kod, bir PowerPoint sunumunda ızgara aralığını nasıl değiştireceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [IViewProperties](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)