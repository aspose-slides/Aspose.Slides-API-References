---
title: get_Password()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar lösenordet. Läs System::String."
type: docs
weight: 105
url: /sv/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() metod


Hämtar lösenordet. Läs [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Anmärkningar


Lösenordet. 

Följande exempel kod visar hur du öppnar lösenordsskyddad PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// arbeta med avkrypterad presentation
```

## Se även

* Klass [String](../../../system/string/)
* Klass [LoadOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)