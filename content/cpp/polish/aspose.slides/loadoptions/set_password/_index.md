---
title: set_Password()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Ustawia hasło. Zapisz System::String."
type: docs
weight: 118
url: /pl/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) metoda


Ustawia hasło. Zapisz [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Uwagi


Hasło. 

Poniższy przykładowy kod pokazuje, jak otworzyć zabezpieczony hasłem plik PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// pracuj z odszyfrowaną prezentacją
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [LoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)