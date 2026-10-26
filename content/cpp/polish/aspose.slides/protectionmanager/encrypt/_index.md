---
title: Encrypt()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Szyfruje prezentację przy użyciu określonego hasła.
type: docs
weight: 105
url: /pl/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) metoda



Szyfruje [Presentation](../../presentation/) przy określonym haśle.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Hasło. |
## Uwagi



Poniższy przykładowy kod pokazuje, jak zaszyfrować plik PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ProtectionManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)