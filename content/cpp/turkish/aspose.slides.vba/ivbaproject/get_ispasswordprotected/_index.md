---
title: get_IsPasswordProtected()
second_title: Aspose.Slides için C++ API Referansı
description: VBAProject'in proje özelliklerini görüntülemek için bir parola ile korunup korunmadığını gösterir. Salt okunur bool.
type: docs
weight: 40
url: /tr/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() metot


VBAProject'in proje özelliklerini görüntülemek için bir parola ile korunup korunmadığını gösterir. Salt Okunur **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Sınıf [IVbaProject](../)
* Ad Alanı [Aspose::Slides::Vba](../../)
* Kütüphane [Aspose.Slides](../../../)