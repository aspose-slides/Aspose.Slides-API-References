---
title: SetWriteProtection()
second_title: Aspose.Slides för C++ API-referens
description: Ställ in skrivskydd för den här presentationen med angivet lösenord.
type: docs
weight: 131
url: /sv/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) metod


Ställ in skrivskydd för den här presentationen med angivet lösenord.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | [System::String](../../../system/string/) | Lösenordet. |
## Anmärkningar



Följande exempelprogram visar hur du ställer in ett skrivskydd för en presentation. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [String](../../../system/string/)
* Klass [ProtectionManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)