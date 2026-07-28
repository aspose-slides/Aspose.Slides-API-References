---
title: SetWriteProtection()
second_title: Aspose.Slides dla C++ Referencja API
description: Ustaw ochronę przed zapisem dla tej prezentacji przy użyciu określonego hasła.
type: docs
weight: 131
url: /pl/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) metoda


Ustaw ochronę przed zapisem dla tej prezentacji przy użyciu określonego hasła.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Hasło. |
## Uwagi



Poniższy przykładowy kod pokazuje, jak ustawić ochronę przed zapisem w prezentacji. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ProtectionManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)