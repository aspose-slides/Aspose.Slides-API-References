---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API Referansı
description: VBAProject'in proje özelliklerini görüntülemek için bir parola ile korumalı olup olmadığını gösterir. Salt okunur bool.
type: docs
weight: 40
url: /tr/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() metodu


VBAProject'in proje özelliklerini görüntülemek için bir parola ile korumalı olup olmadığını gösterir. Salt Okunur **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Ayrıca Bakınız

* Sınıf [VbaProject](../)
* İsim Uzayı [Aspose::Slides::Vba](../../)
* Kütüphane [Aspose.Slides](../../../)