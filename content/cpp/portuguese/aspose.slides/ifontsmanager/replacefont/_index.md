---
title: ReplaceFont()
second_title: Referência da API do Aspose.Slides para C++
description: Substituir fonte na apresentação
type: docs
weight: 118
url: /pt/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) method


Substituir fonte na apresentação

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Fonte de origem |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Fonte de destino |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) method


Substituir fonte na apresentação usando as informações fornecidas em [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Informações de substituição de fonte |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) method


Substituir fonte na apresentação usando as informações fornecidas na coleção de [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Coleção de informações de substituição de fonte |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontData](../../ifontdata/)
* Classe [IFontsManager](../)
* Classe [IFontSubstRule](../../ifontsubstrule/)
* Classe [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)