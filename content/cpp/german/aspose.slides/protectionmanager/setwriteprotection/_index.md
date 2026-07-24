---
title: SetWriteProtection()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt den Schreibschutz für diese Präsentation mit dem angegebenen Passwort.
type: docs
weight: 131
url: /de/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) Methode

Set write protection for this presentation with specified password.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Das Passwort. |
## Hinweise

Der folgende Beispielcode zeigt, wie Sie einen Schreibschutz für eine Präsentation festlegen.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ProtectionManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)