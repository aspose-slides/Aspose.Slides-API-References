---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém a recomendação de somente leitura. Retorna bool.
type: docs
weight: 79
url: /pt/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() método


Obtém a recomendação de somente leitura. Retorna **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Observações


O código de exemplo a seguir mostra como definir um PowerPoint [Presentation](../../presentation/) como somente leitura em C# usando [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Veja também

* Classe [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)