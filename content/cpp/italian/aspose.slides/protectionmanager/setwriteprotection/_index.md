---
title: SetWriteProtection()
second_title: Aspose.Slides per C++ Riferimento API
description: Imposta la protezione in scrittura per questa presentazione con la password specificata.
type: docs
weight: 131
url: /it/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) method

Imposta la protezione in scrittura per questa presentazione con la password specificata.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La password. |

## Osservazioni

Il seguente codice di esempio mostra come impostare una protezione in scrittura a una presentazione.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ProtectionManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)