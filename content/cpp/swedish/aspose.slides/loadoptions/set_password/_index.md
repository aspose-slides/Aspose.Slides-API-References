---
title: set_Password()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in lösenordet. Skriv System::String."
type: docs
weight: 118
url: /sv/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) metod


Ställer in lösenordet. Skriv [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Anmärkningar


Lösenordet. 

Följande exempelprogram visar hur du öppnar lösenordsskyddad PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// arbeta med dekrypterad presentation
```

## Se även

* Klass [String](../../../system/string/)
* Klass [LoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)