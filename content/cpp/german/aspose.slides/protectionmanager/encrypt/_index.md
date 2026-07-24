---
title: Encrypt()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschlüsselt Präsentation mit dem angegebenen Passwort.
type: docs
weight: 105
url: /de/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) Methode


Verschlüsselt [Presentation](../../presentation/) mit dem angegebenen Passwort.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Das Passwort. |
## Hinweise



Der folgende Beispielcode zeigt, wie Sie eine PowerPoint [Presentation](../../presentation/) verschlüsseln. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)