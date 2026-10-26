---
title: get_ReadOnlyRecommended()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la raccomandazione di sola lettura. Legge bool.
type: docs
weight: 79
url: /it/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() metodo

Restituisce la raccomandazione di sola lettura. Legge **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [IProtectionManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)