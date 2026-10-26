---
title: get_Password()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ruft das Passwort ab. Lesen Sie System::String."
type: docs
weight: 105
url: /de/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() Methode

Ruft das Passwort ab. Lesen [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Hinweise

Das Passwort.

Der folgende Beispielcode zeigt, wie man eine passwortgeschützte PowerPoint [Presentation](../../presentation/) öffnet.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// Arbeit mit entschlüsselter Präsentation
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [LoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)