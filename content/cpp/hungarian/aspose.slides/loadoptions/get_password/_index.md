---
title: get_Password()
second_title: Aspose.Slides C++ API referencia
description: "Lekéri a jelszót. Olvassa el a System::String-et."
type: docs
weight: 105
url: /hu/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() metódus


Lekéri a jelszót. Olvassa el [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Megjegyzések


A jelszó. 

Az alábbi mintakód bemutatja, hogyan nyitható meg jelszóval védett PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [LoadOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)