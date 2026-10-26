---
title: Encrypt()
second_title: Riferimento API di Aspose.Slides per C++
description: Cripta la presentazione con la password specificata.
type: docs
weight: 105
url: /it/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) metodo

Cripta [Presentation](../../presentation/) con la password specificata.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | La password. |
## Osservazioni



Il seguente codice di esempio mostra come cripitare un PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)