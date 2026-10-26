---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in rekommendation för skrivskydd. Skriver bool.
type: docs
weight: 92
url: /sv/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) metod


Ställer in rekommendation för skrivskydd. Skriver **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [IProtectionManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)