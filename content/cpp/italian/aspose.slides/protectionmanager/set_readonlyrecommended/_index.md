---
title: set_ReadOnlyRecommended()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta la raccomandazione di sola lettura. Scrivi bool.
type: docs
weight: 92
url: /it/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) metodo

Imposta la raccomandazione di sola lettura. Scrivi **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Osservazioni

Il codice di esempio seguente mostra come impostare un PowerPoint [Presentation](../../presentation/) a sola lettura in C# usando [Aspose.Slides](../../).
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [ProtectionManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)