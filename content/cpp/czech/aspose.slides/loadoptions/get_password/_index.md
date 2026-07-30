---
title: get_Password()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá heslo. Přečtěte System::String."
type: docs
weight: 105
url: /cs/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() metoda


Získá heslo. Přečtěte si [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Poznámky


Heslo. 

Následující ukázkový kód ukazuje, jak otevřít chráněný heslem PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// pracujte s dešifrovanou prezentací
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [LoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)