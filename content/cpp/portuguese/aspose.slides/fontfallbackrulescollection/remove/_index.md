---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove a primeira ocorrência de uma regra FallBack específica da coleção.
type: docs
weight: 53
url: /pt/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) method

Remove a primeira ocorrência de uma regra FallBack específica da coleção.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | A regra a ser removida da coleção. |

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
//Removendo
rulesList->Remove(firstRule);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IFontFallBackRule](../../ifontfallbackrule/)
* classe [FontFallBackRulesCollection](../)
* namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)