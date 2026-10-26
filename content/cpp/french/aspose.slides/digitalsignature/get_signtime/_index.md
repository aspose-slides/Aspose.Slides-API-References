---
title: get_SignTime()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le moment où le document a été signé. Lecture seule System::DateTime."
type: docs
weight: 27
url: /fr/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() méthode


Le moment où le document a été signé. Lecture seule [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## Voir aussi

* Classe [DateTime](../../../system/datetime/)
* Classe [DigitalSignature](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)