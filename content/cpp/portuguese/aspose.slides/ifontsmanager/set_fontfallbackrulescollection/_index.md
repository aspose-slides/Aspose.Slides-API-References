---
title: set_FontFallBackRulesCollection()
second_title: Referência da API Aspose.Slides para C++
description: Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas por meio da funcionalidade de fallback. Escreva IFontFallBackRulesCollection.
type: docs
weight: 40
url: /pt/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) método

Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas pela funcionalidade de fallback. Escreva [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Observações

```cpp
auto pres = MakeObject<Presentation>();
// Obtendo uma coleção de regras vazia ou pré-inicializada do FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// adicionando regras à coleção
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ou
// inicialização de nova instância da coleção de regras
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// adicionando regras à coleção
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// e substituindo a coleção existente pela nova no FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Classe [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)