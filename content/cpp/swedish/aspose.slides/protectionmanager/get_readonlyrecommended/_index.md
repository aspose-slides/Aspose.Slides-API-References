---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar rekommendation för skrivskydd. Läs bool.
type: docs
weight: 79
url: /sv/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() metod


Hämtar rekommendation för skrivskydd. Läser **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Anmärkningar


Följande exempel visar hur du ställer in en PowerPoint [Presentation](../../presentation/) till Skrivskyddad i C# med hjälp av [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Se också

* Klass [ProtectionManager](../)
* Namnutrymme [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)