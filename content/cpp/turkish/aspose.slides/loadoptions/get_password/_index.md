---
title: get_Password()
second_title: Aspose.Slides for C++ API Referansı
description: "Parolayı alır. System::String'i okuyun."
type: docs
weight: 105
url: /tr/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() metod


Parolayı alır. Okuyun [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Açıklamalar


Parola.

Aşağıdaki örnek kod, parola korumalı PowerPoint [Presentation](../../presentation/)'i nasıl açacağını gösterir. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [LoadOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)