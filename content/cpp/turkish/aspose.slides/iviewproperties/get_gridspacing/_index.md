---
title: get_GridSpacing()
second_title: Aspose.Slides C++ API Referansı
description: Sunum belgesinin altındaki ızgara için kullanılacak ızgara aralığını nokta cinsinden döndürür. Okunur float.
type: docs
weight: 92
url: /tr/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() metodu


Sunum belgesinin altındaki ızgara için kullanılacak ızgara aralığını, nokta cinsinden döndürür. Okunur **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Açıklamalar


Izgara aralığı değeri pozitif bir sayı olmalıdır. Tipik değer aralığı 1 mm (2.8349607 nokta) ile 2 inç (144 nokta) arasındadır. 

Aşağıdaki örnek kod, PowerPoint sunumunda ızgara aralığını nasıl değiştireceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [IViewProperties](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)