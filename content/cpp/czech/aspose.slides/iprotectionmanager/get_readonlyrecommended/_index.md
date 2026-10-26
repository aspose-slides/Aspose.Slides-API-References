---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides pro C++ API Reference
description: Získá doporučení pro režim jen pro čtení. Čte **bool**.
type: docs
weight: 79
url: /cs/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() metoda


Získá doporučení pro režim jen pro čtení. Čte **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IProtectionManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)