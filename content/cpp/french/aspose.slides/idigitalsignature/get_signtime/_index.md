---
title: get_SignTime()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le moment où le document a été signé. Lecture seule System::DateTime."
type: docs
weight: 27
url: /fr/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() méthode

Le moment où le document a été signé. Lecture seule [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Voir aussi

* Classe [DateTime](../../../system/datetime/)
* Classe [IDigitalSignature](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)