---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a regra no índice especificado. Somente leitura IFontFallBackRule.
type: docs
weight: 1
url: /pt/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) method


Obtém a regra no índice especificado. Somente leitura [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Observações



```cpp
auto pres = MakeObject<Presentation>();
//Obtendo a coleção de regras vazia ou pré-inicializada do FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Adicionando várias regras à coleção
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Recuperando o objeto da primeira regra na coleção
auto firstRule = rulesList->idx_get(0);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [IFontFallBackRulesCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)