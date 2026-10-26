---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca rekomendację tylko do odczytu. Odczytaj bool.
type: docs
weight: 79
url: /pl/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() metoda


Zwraca rekomendację tylko do odczytu. Odczytaj **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Uwagi


Poniższy kod przykładowy pokazuje, jak ustawić PowerPoint [Presentation](../../presentation/) jako tylko do odczytu w C# przy użyciu [Aspose.Slides](../../).
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [ProtectionManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)