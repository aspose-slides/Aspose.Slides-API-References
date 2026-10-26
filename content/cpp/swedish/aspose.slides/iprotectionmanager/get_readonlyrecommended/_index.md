---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar rekommendation för skrivskydd. Läs bool.
type: docs
weight: 79
url: /sv/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() metod


Hämtar rekommendation för skrivskydd. Läs **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
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