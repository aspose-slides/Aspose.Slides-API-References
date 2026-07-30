---
title: get_ReadOnlyRecommended()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene la raccomandazione di sola lettura. Restituisce bool.
type: docs
weight: 79
url: /it/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() metodo


Ottiene la raccomandazione di sola lettura. Restituisce **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Osservazioni


Il seguente codice di esempio mostra come impostare un PowerPoint [Presentation](../../presentation/) in sola lettura in C# usando [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [ProtectionManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)