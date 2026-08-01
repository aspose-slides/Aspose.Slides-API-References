---
title: set_Password()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het wachtwoord in. Schrijf System::String."
type: docs
weight: 118
url: /nl/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) methode

Stelt het wachtwoord in. Schrijf [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Opmerkingen

Het wachtwoord. 

De volgende voorbeeldcode laat zien hoe een wachtwoordbeveiligde PowerPoint [Presentation](../../presentation/) te openen. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [LoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)