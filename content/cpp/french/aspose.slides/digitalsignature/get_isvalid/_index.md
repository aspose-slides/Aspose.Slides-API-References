---
title: get_IsValid()
second_title: Référence de l'API Aspose.Slides pour C++
description: Si cette signature numérique est valide et que le document n'a pas été altéré, cette valeur sera vraie. Lecture seule bool.
type: docs
weight: 14
url: /fr/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() méthode

Si cette signature numérique est valide et que le document n'a pas été altéré, cette valeur sera vraie. Lecture seule **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Voir aussi

* Classe [DigitalSignature](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)