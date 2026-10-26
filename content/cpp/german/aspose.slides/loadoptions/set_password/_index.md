---
title: set_Password()
second_title: Aspose.Slides für C++ API Referenz
description: "Setzt das Passwort. Schreiben Sie System::String."
type: docs
weight: 118
url: /de/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) Methode


Setzt das Passwort. Schreiben Sie [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Anmerkungen


Das Passwort. 

Der folgende Beispielcode zeigt, wie man eine passwortgeschützte PowerPoint [Presentation](../../presentation/) öffnet. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [LoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)