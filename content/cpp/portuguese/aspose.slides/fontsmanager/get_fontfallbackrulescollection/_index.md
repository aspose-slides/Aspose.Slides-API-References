---
title: get_FontFallBackRulesCollection()
second_title: Referência da API Aspose.Slides para C++
description: Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas pela funcionalidade de fallback. Consulte IFontFallBackRulesCollection.
type: docs
weight: 27
url: /pt/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() método

Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas pela funcionalidade de fallback. Consulte [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Observações

```cpp
auto pres = MakeObject<Presentation>();
// Obtendo a coleção de regras vazia ou pré-inicializada do FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// adicionando regras à coleção
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ou
// inicialização de uma nova instância da coleção de regras
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// adicionando regras à coleção
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// e substituindo a coleção existente pela nova no FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Classe [FontsManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)