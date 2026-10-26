---
title: set_Password()
second_title: Aspose.Slides için C++ API Referansı
description: "Parolayı ayarlar. System::String yazın."
type: docs
weight: 118
url: /tr/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) metodu


Parolayı ayarlar. Yaz [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Açıklamalar


Parola. 

Aşağıdaki örnek kod, şifre korumalı PowerPoint [Presentation](../../presentation/) dosyasını nasıl açacağını gösterir. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// şifreli çözülmüş sunumla çalış
```

## Ayrıca

* Sınıf [String](../../../system/string/)
* Sınıf [LoadOptions](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)