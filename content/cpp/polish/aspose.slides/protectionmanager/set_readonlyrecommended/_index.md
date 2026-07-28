---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia zalecenie trybu tylko do odczytu. Zapisz bool.
type: docs
weight: 92
url: /pl/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) metoda

Ustawia zalecenie trybu tylko do odczytu. Zapisz **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Uwagi

Poniższy przykładowy kod pokazuje, jak ustawić PowerPoint [Presentation](../../presentation/) w trybie tylko do odczytu w C# przy użyciu [Aspose.Slides](../../).

```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [ProtectionManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)