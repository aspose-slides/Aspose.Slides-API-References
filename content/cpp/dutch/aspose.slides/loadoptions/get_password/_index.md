---
title: get_Password()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt het wachtwoord op. Lees System::String."
type: docs
weight: 105
url: /nl/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() methode


Haalt het wachtwoord op. Lees [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Opmerkingen


Het wachtwoord. 

De volgende voorbeeldcode laat zien hoe een met wachtwoord beveiligde PowerPoint [Presentation](../../presentation/) geopend kan worden. 
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
* Library [Aspose.Slides](../../../)