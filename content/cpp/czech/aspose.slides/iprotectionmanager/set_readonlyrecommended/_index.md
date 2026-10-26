---
title: set_ReadOnlyRecommended()
second_title: Reference API Aspose.Slides pro C++
description: Nastaví doporučení pro režim jen pro čtení. Zapíše bool.
type: docs
weight: 92
url: /cs/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) metoda


Nastaví doporučení pro režim jen pro čtení. Zapisuje **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
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