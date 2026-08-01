---
title: SetWriteProtection()
second_title: Aspose.Slides voor C++ API-referentie
description: Stel een schrijfbeveiliging in voor deze presentatie met het opgegeven wachtwoord.
type: docs
weight: 131
url: /nl/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) methode


Stel een schrijfbeveiliging in voor deze presentatie met het opgegeven wachtwoord.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Het wachtwoord. |
## Opmerkingen



De volgende voorbeeldcode laat zien hoe u een schrijfbeveiliging instelt voor een presentatie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [ProtectionManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)