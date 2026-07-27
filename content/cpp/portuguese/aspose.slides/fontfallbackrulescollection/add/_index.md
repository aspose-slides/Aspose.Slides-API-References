---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma regra FallBack especificada ao final da coleção.
type: docs
weight: 40
url: /pt/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) método

Adiciona uma regra FallBack especificada ao final da coleção.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Regra especificada para adição |
## Observações

```cpp
auto pres = MakeObject<Presentation>();
//Obtendo a coleção de regras vazia ou pré-inicializada do FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Adicionando nova regra à coleção
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [FontFallBackRulesCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)