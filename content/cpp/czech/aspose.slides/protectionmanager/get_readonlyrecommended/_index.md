---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá doporučení pro režim jen pro čtení. Vrací bool.
type: docs
weight: 79
url: /cs/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() metoda

Získá doporučení pro režim jen pro čtení. Vrací **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
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