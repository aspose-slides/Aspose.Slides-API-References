---
title: set_Password()
second_title: Aspose.Slides C++ API referencia
description: "Beállítja a jelszót. Írja be System::String."
type: docs
weight: 118
url: /hu/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) metódus

Beállítja a jelszót. Írja be [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Megjegyzések

A jelszó. 

A következő mintakód bemutatja, hogyan nyitható meg a jelszóval védett PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [LoadOptions](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)