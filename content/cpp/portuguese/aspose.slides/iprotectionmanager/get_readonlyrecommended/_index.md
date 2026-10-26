---
title: get_ReadOnlyRecommended()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a recomendação de somente leitura. Lê bool.
type: docs
weight: 79
url: /pt/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() método


Obtém a recomendação de somente leitura. Lê **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Veja também

* Classe [IProtectionManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)