---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Nastaví doporučení pro režim jen pro čtení. Zapište bool.
type: docs
weight: 92
url: /cs/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) metoda


Nastaví doporučení pro režim jen pro čtení. Zapište **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Poznámky


Následující ukázkový kód vám ukazuje, jak nastavit PowerPoint [Presentation](../../presentation/) na režim jen pro čtení v C# pomocí [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [ProtectionManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)