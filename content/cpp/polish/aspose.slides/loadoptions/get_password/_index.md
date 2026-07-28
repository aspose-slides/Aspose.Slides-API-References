---
title: get_Password()
second_title: Aspose.Slides dla C++ odniesienie API
description: "Pobiera hasło. Przeczytaj System::String."
type: docs
weight: 105
url: /pl/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() metoda


Pobiera hasło. Przeczytaj [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Uwagi


Hasło. 

Poniższy przykładowy kod pokazuje, jak otworzyć chroniony hasłem plik PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [LoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)