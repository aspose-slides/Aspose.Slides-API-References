---
title: set_ReadOnlyRecommended()
second_title: Referência da API Aspose.Slides para C++
description: Define a recomendação de somente leitura. Escreva bool.
type: docs
weight: 92
url: /pt/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) método

Define a recomendação de somente leitura. Escreva **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Ver Também

* Classe [IProtectionManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)