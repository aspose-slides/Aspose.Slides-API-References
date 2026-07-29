---
title: Encrypt()
second_title: Aspose.Slides för C++ API-referens
description: Krypterar Presentation med angivet lösenord.
type: docs
weight: 105
url: /sv/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) metod

Krypterar [Presentation](../../presentation/) med angivet lösenord.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Lösenordet. |
## Anmärkningar

Följande exempelkod visar hur du krypterar en PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Se också

* Klass [String](../../../system/string/)
* Klass [ProtectionManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)