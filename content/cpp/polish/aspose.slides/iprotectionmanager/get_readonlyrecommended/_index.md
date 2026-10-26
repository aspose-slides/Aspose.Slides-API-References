---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera rekomendację tylko do odczytu. Odczyt bool.
type: docs
weight: 79
url: /pl/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() metoda

Pobiera rekomendację tylko do odczytu. Odczyt **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [IProtectionManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)