---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia rekomendację tylko do odczytu. Zapisz bool.
type: docs
weight: 92
url: /pl/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) metoda


Ustawia rekomendację tylko do odczytu. Zapisz **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
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