---
title: SetWriteProtection()
second_title: Aspose.Slides pro C++ API Reference
description: Nastavte ochranu proti zápisu pro tuto prezentaci s určeným heslem.
type: docs
weight: 131
url: /cs/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) metoda

Nastavte ochranu proti zápisu pro tuto prezentaci se zadaným heslem.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Heslo. |
## Poznámky

Následující ukázkový kód vám ukáže, jak nastavit ochranu proti zápisu prezentaci. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [ProtectionManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)