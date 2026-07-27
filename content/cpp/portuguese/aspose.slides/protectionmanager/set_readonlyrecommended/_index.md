---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides para C++ Referência da API
description: Define a recomendação de somente leitura. Escreva bool.
type: docs
weight: 92
url: /pt/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) método


Define a recomendação de somente leitura. Escreva **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Observações


O código de exemplo a seguir mostra como definir um [Presentation](../../presentation/) do PowerPoint como Somente Leitura em C# usando [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Veja também

* Classe [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)