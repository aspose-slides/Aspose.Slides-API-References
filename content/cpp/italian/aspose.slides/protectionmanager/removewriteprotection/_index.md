---
title: RemoveWriteProtection()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove la protezione in scrittura per questa presentazione.
type: docs
weight: 144
url: /it/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() metodo


Rimuove la protezione in scrittura per questa presentazione.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Osservazioni


Questo esempio di codice mostra come rimuovere la protezione in scrittura da un PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [ProtectionManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)