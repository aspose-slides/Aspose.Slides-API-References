---
title: set_Password()
second_title: Aspose.Slides pro C++ referenci API
description: "Nastaví heslo. Zapište System::String."
type: docs
weight: 118
url: /cs/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) metoda

Nastaví heslo. Zapište [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Poznámky

Heslo.

Následující ukázkový kód ukazuje, jak otevřít chráněnou heslem prezentaci PowerPoint [Presentation](../../presentation/).
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [LoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)