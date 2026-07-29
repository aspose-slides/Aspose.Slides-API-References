---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in rekommendation för skrivskydd. Skriv bool.
type: docs
weight: 92
url: /sv/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) metod


Ställer in rekommendation för skrivskydd. Skriv **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Anmärkningar


Följande exempel kod visar hur du ställer in en PowerPoint [Presentation](../../presentation/) till Read-Only i C# med [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [ProtectionManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)