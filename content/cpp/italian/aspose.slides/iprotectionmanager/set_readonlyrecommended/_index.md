---
title: set_ReadOnlyRecommended()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta la raccomandazione di sola lettura. Scrivi bool.
type: docs
weight: 92
url: /it/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) metodo


Imposta la raccomandazione di sola lettura. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
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