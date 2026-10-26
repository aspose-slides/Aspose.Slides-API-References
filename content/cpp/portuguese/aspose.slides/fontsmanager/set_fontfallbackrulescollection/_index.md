---
title: set_FontFallBackRulesCollection()
second_title: Referência da API Aspose.Slides para C++
description: Representa a coleção de regras FontFallBack de um usuário para gerenciar coleções de fontes para substituições corretas pela funcionalidade de fallback Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /pt/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) método

Representa a coleção de regras FontFallBack de um usuário para gerenciar coleções de fontes para substituições corretas pela funcionalidade de fallback Write [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Observações



```cpp
auto pres = MakeObject<Presentation>();
// Obtendo coleção de regras vazia ou pré-inicializada do FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// adicionando regras à coleção
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// or
// inicializando nova instância da coleção de regras
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// adicionando regras à coleção
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// e substituindo a coleção existente pela nova no FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Classe [FontsManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)