---
title: get_GridSpacing()
second_title: Aspose.Slides for C++ API Referansı
description: Sunum belgesinin altındaki ızgara için kullanılacak ızgara aralığını, nokta cinsinden döndürür. Okunur float.
type: docs
weight: 92
url: /tr/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() metod


Sunum belgesinin altındaki ızgara için kullanılacak ızgara aralığını, nokta cinsinden döndürür. Okunur **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Açıklamalar


Izgara aralığı değeri pozitif bir sayı olmalıdır. Tipik değer aralığı 1 mm (2.8349607 nokta) ile 2 inç (144 nokta) arasındadır. 

Aşağıdaki örnek kod, PowerPoint sunumunda ızgara aralığını nasıl değiştireceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Sınıf [ViewProperties](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)